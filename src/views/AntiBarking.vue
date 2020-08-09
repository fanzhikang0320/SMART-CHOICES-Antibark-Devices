<template>
  <div class="mosquito-wrapper">
        <div class="maskLayer">
                <div class="mask-content ">
                    <span class="close"></span>
                    <a :href="mainLink" target="_blank" class="mask-box clearfix">
                        <div class="mask-left">
                            <img src="@/assets/image/barking/alert-ad.jpg" alt="" class="ad">
                        </div>
                        <div class="mask-right">
                            <p class="offer">Limited Time Offer</p>
                            <p class="save"><span>SAVE</span><strong>50% MONEY</strong></p>
                            <p class="OEI">Offer Expires In</p>
                            
                            <div class="date-area">
                                <div class="time-box colon">
                                    <span class="text">Hours</span>
                                    <div class="time">
                                        <span class="hours-decade">0</span>
                                        <span class="hours-unit">0</span>
                                    </div>
                                </div>
                                <div class="time-box colon">
                                    <span class="text">Minutes</span>
                                    <div class="time">
                                        <span class="minutes-decade">0</span>
                                        <span class="minutes-unit">0</span>
                                    </div>
                                </div>
                                <div class="time-box">
                                    <span class="text">Seconds</span>
                                    <div class="time">
                                        <span class="seconds-decade">0</span>
                                        <span class="seconds-unit">0</span>
                                    </div>
                                </div>
                            </div>
                            <p class="desc">30 Days Money Back Guarantee</p>
                            <a :href="mainLink" target="_blank" rel="noopener noreferrer" class="btn">Get the discount today!</a>
                        </div>
                    </a>
                </div>
        </div>
      <header class="mosquito-header">
          <div class="header-left">
                <img src="@/assets/image/logo.png" alt="SMART CHOICES" class="logo">
                <p class="text">Control dog's barking and transform your dog to the well-behaved friend</p>
          </div>
          <a href="/" class="btn">Top4 Anti-Barking Devices</a>

      </header>
      <section class="banner">
          <div class="banner-container">
               <div class="banner-content">
                    <h1 class="g">2020’s TOP 4</h1>
                    <h1 class="a">Anti-Barking Devices</h1>
                </div>
          </div>
          
      </section>
      <main class="container">
          <div class="desc-area">
              <h2 class="area-title">The Best Anti-Barking Devices In 2020</h2>
              <div class="desc-content">
                    <p>Do you own a dog that often gets out of control?  Is dog barking driving you crazy?</p>
                    <p>The secret that helps best trainers get excellent results and improve bad dog behavior is finally revealed! This new ultrasonic device can control your own dog’s barking and transform your dog to the well-behaved best friend you remember.</p>
                    <p>Our researchers tested the five most popular anti barking devices on the market in terms of price, product quality, ease of use, range, effectiveness and discount. </p>
              </div>
          </div>
          <div class="product-area">
              <p class="product-area-title">Here is a list of their rankings:</p>
              <WifiProduct/>
          </div>
          <div class="why-area">
              <h2 class="area-title">Why BarxBuddy is Our Top Choice?</h2>
              <div class="why-container">
                  <img src="@/assets/image/barking/info.jpg" alt="" class="info">
                  <div class="content">
                    <p>BarxBuddy is the best-used device to make an unfriendly dog polite and silent with the help of ultrasonic dog whistle. This is one of the hottest and effective dog products that have helped millions of pet owners to make their four-legged friend polite. Besides that, it works on several dog breeds like Labradors, Beagles, German Sheppard’s, Huskies, Rottweiler’s, Pit bulls, boxers, poodles, pinschers, daschunds, and various cat breeds.</P>
                    <p>Dogs are great, but they are much better when they are trained properly. This device is perfect for dog owners and anyone who fears dogs.</P>
                    <p>Dogs want to please us and make us happy, but sometimes they don't understand what they should and should not do. It can be challenging and embarassing dealing with unwanted behaviors. Training is the best way to stop bad behavior and encourage the good, but it isn't easy to communicate with our furry friends. That's where BarxBuddy can help. It allows you to give immediate feedback and helps your dog focus on the instructions. Take control and you can train and reward, making your dog the perfect pet you always wanted.</P>
                    <p>With BarxBuddy, you can train your dog any time and any place.</P>
                  </div>
              </div>
          </div>
          <div class="special-area">
              <div class="special-container">
                    <h3 class="offer">Special Offer on Now!</h3>
                    <p class="sub">BarxBuddy is now <span class="red">on sale!</span> Today for a <span class="red">Limited Time Discount!</span></p>
                    
            
                    <img src="@/assets/image/barking/special-ad.jpg" alt="" class="picture">
                    <a :href="mainLink" target="_blank" rel="noopener noreferrer" class="btn"> Get Your Barxbuddy Today!</a>
                    <p class="desc-content">Quantities are limited, these Anti-Barking devices like <a :href="mainLink" target="_blank" rel="noopener noreferrer">BarxBuddy</a> sold out very quickly,so be sure to order right away!</p>
                </div>
          </div>
          <div class="faq-area">
              <h2 class="area-title">FAQ</h2>
              <div class="question-box">
                  <div class="question-item" v-for="(item,index) in questionData" :key="index">
                      <h3 class="question-title">{{item.title}}</h3>
                      <div class="question-content" v-html="item.content"></div>
                  </div>
              </div>
          </div>
      </main>
  </div>
</template>

<script>
import WifiProduct from '@/components/wifi-product.vue'
import $ from 'jquery'
export default {
    components: {
        WifiProduct
    },
    data() {
        return {
            mainLink: 'https://antibark-devices.smartchoice.reviews/barkingdetail',
            questionData: [
                {
                    title: 'How it works?',
                    content: `<p>Every time the dog barks your training device will activate automatically. Depending on the device, he'll hear an annoying high-pitched tone or feel a sudden vibration – absolutely no shock. This directs their attention away from whatever they were barking at. The dog will learn that his barking is causing the irritating sound or vibration, so he slows down and eventually stops. Some dogs figure it out right away, others might take a couple weeks.</p>`
                },
                {
                    title: 'Is it harmful for dogs?',
                    content: `<p>Those devices use high pitched tones, not detectable by humans, that specifically target a dog's hearing. Use the ultrasonic sound to stop your dog in the middle of unwanted behavior, like barking or chewing on shoes. So it is 100% HARMLESS TO DOGS, HUMANS, AND ALL ANIMALS.</p>`
                },
                {
                    title: 'Is it suitable for all kinds of dogs?',
                    content: `<p>Absolutly, this product suit for most kinds of dogs, like Labradors, Beagles, German Sheppard’s, Huskies, Rottweiler’s, Pit bulls, boxers, poodles, pinschers, daschunds, and various cat breeds.</p>`
                }
            ],
            timer: null,
            count: 0
        }
    },
    methods: {
        /**
         * 倒计时
         */
        countDown() {
            //结束时间
            let finishTime = new Date('2020/7/28').getTime();
            let startTime = new Date(new Date().toLocaleDateString()).getTime();
            let intervalTime = 0,
                day = 0,
                hours = 0,
                minutes = 0,
                seconds = 0;
            let that = this;
            this.timer = setInterval(function () {
                if (finishTime - new Date().getTime() <= 0) {
                     finishTime = new Date(new Date().toLocaleDateString()).getTime() + 1 * 24 * 60 * 60 * 1000;
                }
                intervalTime = finishTime - new Date().getTime();

                day =  Math.floor(intervalTime/(1000*60*60*24));
                hours = Math.floor(intervalTime / (60 * 60 * 1000) % 24) + day * 24;
                minutes = Math.floor(intervalTime / (60 * 1000) % 60);
                seconds = Math.floor(intervalTime / 1000 % 60); 
                that.renderTime(hours,minutes,seconds);
                
            },1000)
            
        },
        renderTime(hours,minutes,seconds) {
            let hoursObj = this.splitCell(hours);
            let minutesObj = this.splitCell(minutes);
            let secondsObj = this.splitCell(seconds);
            $('.hours-decade').text(hoursObj.decade);
            $('.hours-unit').text(hoursObj.unit);
            $('.minutes-decade').text(minutesObj.decade);
            $('.minutes-unit').text(minutesObj.unit);
            $('.seconds-decade').text(secondsObj.decade);
            $('.seconds-unit').text(secondsObj.unit);

        },
        splitCell(num) {
            let unit = Math.floor(num % 10);
            let decade = Math.floor(num / 10);
            return {
                unit: unit,
                decade: decade
            }
        },
        alert() {
            $('.maskLayer').css({
                display: 'block'
            })
            $('.mask-content').animate({
              opacity: 1,
              top: '50%'
            },300)
        }
    },
    mounted() {
        this.countDown();
        let that = this;
        $('body').on('mouseenter',function () {
            $('body').one('mouseleave',function () {
                if (that.count == 0) {

                    that.alert();
                }
                that.count ++;
            })
        })
        $('.close').on('click',function (event) {
            event.stopPropagation();
            $('.maskLayer').css({
                display: 'none'
            })
            clearInterval(that.timer);
        })
        $('.maskLayer').on('click',function (e) {
            e.stopPropagation();
            $('.maskLayer').css({
                display: 'none'
            })
            clearInterval(that.timer);
        })
    },
    beforeDestroy() {
        $('body').off('mouseenter');
        clearInterval(this.timer);
        this.timer = null;
    }
}
</script>

<style lang="less" scoped>
@import url('../assets/css/AntiBarking.less');
</style>