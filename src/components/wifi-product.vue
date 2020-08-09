<template>
  <div class="product-wrapper">
      <div :class="{'product-item': true, 'first-item': index == 0, 'last-item': index == productList.length - 1}" v-for="(product,index) in productList" :key="index">
          <div class="circle" v-if="index != productList.length- 1">
              <span class="num">{{index + 1}}</span>
          </div>
          <div class="corner-box" v-if="index == 0">
              <span class="text">50% Discount Today!</span>
          </div>
          <div class="big-title" v-if="index == productList.length - 1">The Most Popular Anti-Barking Devices In 2020</div>
          <a :href="product.link" @click.stop="handleExecute(index)" target="_blank" class="product-link-box">
            <div class="product-container">
                <div class="product-container-left">
                    <div class="picture-box">
                        <img :src="product.picture" :alt="product.name" class="picture">
                    </div>
                    <div class="desc-list-box">
                        <h2 class="product-name">{{product.name}}</h2>
                        <ul class="list-box">
                            <li v-for="(item,id) in product.list" :key="id">
                                <span class="icon"></span>
                                <p class="text">{{item.text}}</p>
                            </li>
                        </ul>
                        <p class="buys" v-if="index == 0 || index == productList.length - 1">More than {{product.buys}} people choose {{product.name}} Today!</p>
                    </div>
                </div>
                <div class="product-container-right">
                    <p class="good">
                        <span class="text">{{index == 0 || index == productList.length - 1 ? 'Excellent': index == 1 ? 'Very Good': 'Good'}}</span>
                        <span class="king-icon" v-if="index == 0 || index == productList.length - 1"></span>
                        <span class="good-icon" v-if="index == 1"></span>
                    </p>
                    <p class="rate-box"><span class="score">{{product.score}}</span><span>/10</span></p>
                    <a :href="product.link" @click.stop="handleExecute(index)" target="_blank" class="btn">
                        <span class="text">Visit Site</span>
                        <span class="icon"></span>
                    </a>
                    <!-- <a :href="product.reviewLink" class="review">Read Our Review</a> -->
                </div>
            </div>
          </a>
      </div>
      
  </div>
</template>

<script>
export default {
    data() {
        return {
            productList: [
                {
                    id: 1,
                    name: 'BarkBuddy',
                    picture: require('@/assets/image/barking/BB.png'),
                    link: 'https://antibark-devices.smartchoice.reviews/barkingdetail',
                    reviewLink: '',
                    buys: 828,
                    list: [
                        {
                            text: 'Non-violent, not harmful at all to dogs'
                        },
                         {
                            text: 'Arrives with LED light that helps for a night walk'
                        },
                         {
                            text: 'Easy to Use'
                        },
                        {
                            text: 'Suitable for all dog breeds'
                        },
                         {
                            text: 'Works for long hours in a single charge'
                        },
                         {
                            text: 'Has durable features that works for long years'
                        },
                        {
                            text: 'Waterproof device'
                        },
                        {
                            text: 'Train your dog any time and any place'
                        }
                    ],
                    score: '9.8'

                },
                {
                    id: 2,
                    name: 'BarXStop',
                    picture: require('@/assets/image/barking/BXS.png'),
                    link: 'https://hypertechx.com/ps/barxstop/index.php?net=9785&aff={AFFID}&sid={SUBID}&cid={CLICKID}',
                    reviewLink: '',
                    buys: 828,
                    list: [
                        {
                            text: 'Non-violent, not harmful at all to dogs'
                        },
                        {
                            text: 'Multiple training modes'
                        },
                        {
                            text: 'Train your dogs easily'
                        },
                        {
                            text: 'Effective solution'
                        },
                        {
                            text: 'The range is wide'
                        }
                    ],
                    score: '9.6'
                },
                {
                    id: 3,
                    name: 'MODUS',
                    picture: require('@/assets/image/barking/M.png'),
                    link: 'https://amzn.to/30uQfPN',
                    reviewLink: '',
                    buys: 828,
                    list: [
                        {
                            text: 'No skills required and easy to control'
                        },
                        {
                            text: 'Safe to use'
                        },
                        {
                            text: 'Wide control range'
                        },
                        {
                            text: 'Ergonomic design'
                        }
                    ],
                    score: '9.5'
                },
                {
                    id: 4,
                    name: 'NPS',
                    picture: require('@/assets/image/barking/NPS.png'),
                    link: 'https://amzn.to/39qFwtP',
                    reviewLink: '',
                    buys: 828,
                    list: [
                        {
                            text: 'Hands-free'
                        },
                        {
                            text: 'Fast, strong, stable signal'
                        },
                        {
                            text: 'Feel secure'
                        },
                        {
                            text: 'Plug and play connection'
                        }
                    ],
                    score: '9.2'
                },
                {
                    id: 1,
                    name: 'BarkBuddy',
                    picture: require('@/assets/image/barking/BB.png'),
                    link: 'https://antibark-devices.smartchoice.reviews/barkingdetail',
                    reviewLink: '',
                    buys: 828,
                    list: [
                        {
                            text: 'Non-violent, not harmful at all to dogs'
                        },
                         {
                            text: 'Arrives with LED light that helps for a night walk'
                        },
                         {
                            text: 'Easy to Use'
                        },
                        {
                            text: 'Suitable for all dog breeds'
                        },
                         {
                            text: 'Works for long hours in a single charge'
                        },
                         {
                            text: 'Has durable features that works for long years'
                        },
                        {
                            text: 'Waterproof device'
                        },
                        {
                            text: 'Train your dog any time and any place'
                        }
                    ],
                    score: '9.8'

                }
            ]
        }
    },
    methods: {
        handleExecute(index) {
            if (index == 0 || index == this.productList.length - 1) return false;
            window.execute();
        }
    }

}
</script>

<style lang="less" scoped>
@import url('../assets/css/wifi-product.less');
</style>