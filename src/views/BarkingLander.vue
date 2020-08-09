<template>
  <div class="barkingLander-wrapper">
      <header>
          <div class="mosquito-header">
            <div class="header-left">
                    <img src="@/assets/image/logo.png" alt="SMART CHOICES" class="logo">
                    <p class="text">Control dog's barking and transform your dog to the well-behaved friend</p>
            </div>
            <a href="/" class="btn">Top4 Anti-Barking Devices</a>
        </div>
      </header>
      <main class="barkingLander-main clearfix">
          <div class="main-container">
              <h1 class="main-title">
                  <p>Ex-Dog Trainer Reveals</p>
                  <p class="g">– Stop Bad Behavior With This!</p>
              </h1>
              <div class="article-area">
                  <div class="article-top">
                      <div class="author-box">
                          <img src="@/assets/image/barkingLander/author.jpg" alt="Kevin Roll" class="headImg">
                          <div class="desc-box">
                              <p>by <span class="name">Kevin Roll</span></p>
                              <p class="date">July 07 2020</p>
                          </div>
                      </div>
                      <div class="share-box">
                          <img src="@/assets/image/barkingLander/facebook.svg" @click="shareFacebook" alt="facebook">
                          <img src="@/assets/image/barkingLander/linkin.svg" @click="shareLinkedin" alt="linkin">
                          <img src="@/assets/image/barkingLander/twitter.svg" @click="shareTwitter" alt="twitter">
                      </div>
                  </div>
                  <div class="article-container">
                      <img src="@/assets/image/barkingLander/article.jpg" alt="" class="picture">
                      <div class="title-box">
                            <h4 class="q-title">- Do you own a dog that often gets out of control?</h4>
                            <h4 class="q-title">- Has your dog bitten the mailman or the paperboy too many times?</h4>
                            <h4 class="q-title">- Is dog barking driving you crazy? </h4>
                      </div>
                      <div class="content">
                          <p>The secret that helps best trainers get excellent results and improve bad dog behavior is finally revealed! This new ultrasonic device can control your own dog’s barking and transform your dog to the well-behaved best friend you remember.</p>
                      </div>
                      
                  </div>
              </div>
              <div class="why-need-area">
                  <h2 class="area-title">Why do you need an anti-barking device?</h2>
                    <div class="content">
                        <p>My name is Kevin Roll and I am a dog trainer. <strong>In fact, I have been training dogs for over 10 years with experience in military dog-training</strong> and also, rescuing dogs from local shelters.</p>
                        <p>I have a lot of stories as every dog that I trained has its own tale and the truth is that I had many, many dogs. Each of these dogs has contributed to my education.</p>
                        <p>However, I decided to describe you my first experience as a dog owner. I do not mind admitting that, when I first became a dog owner, I struggled with my dog’s training and behavioral problems. <strong>My dog, Max, was very aggressive with strangers.</strong> </p>
                        <p>He had bitten many people, even my friends and relatives. The thing is that if I had not introduced you to Max, the chances were that he would attack you when you happened to walk into our yard. </p>
                        <p>His barking was, also, a real problem. <strong>It was very common for Max to start barking at inappropriate times to grab my attention and start playing with him.</strong> When he was seeing a neighbor or jogger out the window, Max was lighting up again.</p>
                        <img src="@/assets/image/barkingLander/l1.jpg" alt="" class="picture">
                        <p>I had trained a lot of dogs and I could not believe that my own dog had such a bad behavior. In fact, I could not believe that my dog attacked people for no reason at all. From my experience, I knew that dogs have reasons for what they do. </p>
                        <p>I tried to find out the real cause of his bad behavior. As in most cases of dog’s aggression, the underlying reason for Max’s bad behavior was fear. I did not know what had happened to him before Max came to live with me, but I was pretty sure that someone did something really bad to him.</p>
                        <p>So, I had to find a solution to make Max stop this unwanted behavior and I tried almost everything. Spray water, mirror training,  giving candy, taking him to the park, even covering the windows with paper and using all the dog-training techniques I was aware of. <strong>But nothing worked.</strong></p>
                        <p>After many more months of torture, <strong>something changed my life</strong>. I was driving home after a very long day at work when, suddenly, I heard on the radio about a <strong>new device</strong> that stops bad dog behavior. In fact, a popular radio show was hosting a professional dog trainer that talked about his new strategy to deal with aggressive dogs, which combined with this device, <strong>had amazing results</strong>. </p>
                    </div>
              </div>
              <div class="what-it-area">
                  <h2 class="area-title">What Is It?</h2>
                  <div class="content">
                      <img src="@/assets/image/barkingLander/l2.jpg" alt="" class="picture">
                      <p>I was, patiently, waiting to hear the name of this new device when, finally, the trainer referred to it as <a :href="mainLink" target="_blank">BarxBuddy</a>. So, when I returned home I searched for more information about this weird device.  It turned out that <a :href="mainLink" target="_blank">BarxBuddy</a> was a completely non-violent pet training device that operated on a frequency only dogs could hear. <strong>It’s kind of like a focused dog whistle.</strong></p>
                        <p>I was skeptical about what I should do or how Max would react but, in the end, I decided to give it a try and ordered BarxBuddy online. In less than a week, it was in my hand and changing my life.</p>
                        <p><strong>When Max started barking at inappropriate times, I started pointing him out by pressing the button</strong>. At first, Max ran away. I pushed it again. It took a couple of days. After one week, he was not even barking if he was seeing me with that in my hand. I no longer had to press the button.</p>
                        <p>I did the same thing when my friends were coming home and Max was ready to attack them. I moved between Max and my friends and pressed the button. The results were amazing! <a :href="mainLink" target="_blank">BarxBuddy</a> had totally improved Max’s bad behavior! </p>
                  </div>
              </div>
              <div class="how-work-area">
                  <h2 class="area-title">How BarxBuddy Works?</h2>
                  <div class="content">
                      <img src="@/assets/image/barkingLander/info.jpg" alt="" class="picture">
                      <p>Wait until your dog begins the behavior that you want to discourage. This could be barking at the front door, continuously barking at guests, digging a hole in the yard, tearing apart your couch cushions, or anything else that dogs do to annoy us humans.</p>
                        <p>After the dog has begun the unwanted behavior, you simply get in between the dog and what’s causing the behavior, point the <a :href="mainLink" target="_blank">BarxBuddy</a> at it, and press and hold the button. It will immediately catch the dog’s attention, backing away from it. Then, simply release the button and make sure to give the dog some kind of reward (treat, head scratches, etc.) to reinforce the good behavior.</p>
                        <p>If your dog is stubborn, the flashing LED light will help catch their attention. Some dogs respond to visual training better, and the LED will ensure the <a :href="mainLink" target="_blank">BarxBuddy</a> is successful for those types of dogs. And the light can double as a flashlight on those night walks, which is always helpful.</p>
                        <p>The <a :href="mainLink" target="_blank">BarxBuddy</a> device also works against unfriendly dogs outside of the home. If a strange dog is acting aggressively toward you or your own dog, you simply press the button to keep it away.</p>
                        <img src="@/assets/image/barkingLander/l3.jpg" alt="" class="picture">

                  </div>
                  <div class="how-work-bottom">
                      <h4 class="work-title">The most interesting part is that it is tested and works on almost all breeds, including:</h4>
                        <ul class="list-box">
                            <li>
                                <span class="icon"></span>
                                <p class="text"><strong>Big dogs</strong> like Akita, German Shepards, Labradors, etc</p>
                            </li>
                            <li>
                                <span class="icon"></span>
                                <p class="text"><strong>Medium dogs</strong> like Barbet, Bull Terrier, Dalmatian, etc.</p>
                            </li>
                            <li>
                                <span class="icon"></span>
                                <p class="text"><strong>Small dogs</strong> like Australian Terrier, Beagles, Bolognese, etc.</p>
                            </li>
                            <li>
                                <span class="icon"></span>
                                <p class="text"><strong>More aggressive breeds</strong> like Rottweilers, Pinschers,  Pitbulls, Boxers, etc.</p>
                            </li>
                        </ul>
                  </div>
              </div>
              <div class="should-area">
                  <h2 class="area-title">Should I Get BarxBuddy?</h2>
                    <div class="content">
                        <p>If you’re having trouble with your pets at home, or you’re worried that you or your dog may be attacked while you’re out for a walk, carry <a :href="mainLink" target="_blank">BarxBuddy</a> to make sure every dog around you, will behave appropriately.</p>
                        <p><strong>This device has been selling out regularly since its debut</strong>. It really is that popular. The amazing reviews and sharing by word of mouth or social media are selling it out, since it hasn’t even been advertised yet. <strong>It’s affordable and a great option to prevent dogs from barking too much or causing damage to your home</strong>.</p>
                    </div>
                    <div class="PC-box">
                        <div class="pc-item">
                            <div class="pc-top">
                                <span class="icon smile-icon"></span>
                                <span class="text">Pros:</span>
                            </div>
                            <ul class="list-box">
                                <li>
                                    <p class="text">● Non-Violent Pet Training Device</p>
                                </li>
                                <li>
                                    <p class="text">● Works On All Breeds</p>
                                </li>
                                <li>
                                    <p class="text">● Recommended By The Best Dog Trainers</p>
                                </li>
                                <li>
                                    <p class="text">● 50% Discount Currently Available</p>
                                </li>
                            </ul>
                        </div>
                        <div class="pc-item">
                            <div class="pc-top">
                                <span class="icon sad-icon"></span>
                                <span class="text">Cons:</span>
                            </div>
                            <ul class="list-box">
                                <li>
                                    <p class="text">● May Be Running Out of Stock Soon</p>
                                </li>
                            </ul>
                        </div>
                    </div>
              </div>
              <div class="where-area">
                  <h2 class="area-title">Where Can I Order BarxBuddy?</h2>
                    <div class="content">
                        <p>Just go to the <a :href="website" target="_blank">official website</a>.  <strong>It’s That Simple!</strong></p>
                        <p>You can also take advantage of the very attractive multiple order discounts that <a :href="mainLink" target="_blank">BarxBuddy</a> is offering. Why not get one for your loved ones or one for your friends?</p>
                    </div>
              </div>
              <div class="get-area">
                  <h5 class="title">Special Offer on Now!</h5>
                  <p class="sub">BarxBuddy is now <span class="s-red">on sale!</span>Order Today for a <span class="b-red">Limited Time Discount!</span></p>
                    <img src="@/assets/image/barkingLander/special-ad.jpg" alt="" class="picture">
                    <a :href="mainLink" target="_blank" rel="noopener noreferrer" class="btn"> Get Your Barxbuddy Today!</a>
                    <p class="desc">Quantities are limited, these Anti-Barking devices like <a :href="mainLink" target="_blank">BarxBuddy</a> sold out very quickly,so be sure to order right away!</p>
              </div>
              <div class="saying-area">
                  <h2 class="saying-title">What People Are Saying</h2>
                    <div class="saying-item">
                        <img src="@/assets/image/barkingLander/say1.png" alt="" class="headImg">
                        <div class="content">
                            <p class="em">Better than I could have imagined!</p>
                            <p class="text">"Wonderful product. I wish I had it years ago. Calmed my beloved house dog right down. He use to bark at everything even the wind. This thing has been a God send!!!!"</p>
                            <p class="name">Joseph J. Douglas</p>
                        </div>
                    </div>
                    <div class="saying-item">
                        <img src="@/assets/image/barkingLander/say2.png" alt="" class="headImg">
                        <div class="content">
                            <p class="em">Immediate Results</p>
                            <p class="text">"Love the size of this unit. It really makes your dog turn around and look at you. He stops barking instantly. It only takes a 9 volt battery. It also has step two if dog runs. It gets the dog to stop. Best park no harm to the doggie. What's awsome is it has a flash light. Perfect if you take doggie out at night. They he won't bark and you can see where he goes."</p>
                            <p class="name">Harvey J. Rodrigues</p>
                        </div>
                    </div>
                    <div class="saying-item">
                        <img src="@/assets/image/barkingLander/say3.png" alt="" class="headImg">
                        <div class="content">
                            <p class="em">Great for my stubborn dog</p>
                            <p class="text">"Have just started to use this and so far is working great. Have hyper two year old Schnauzer who likes let other dogs know he's the boss when out walking. I press it once for a second & it stops him charging and pulling my shoulder from its socket. Also works in house re barking at anything that moves outside (leaves, birds, planes) & hoping it trains him to behave with better manners."</p>
                            <p class="name">Mary A. Davis</p>
                        </div>
                    </div>
              </div>
          </div>
          <div class="main-fixed">
              <div class="main-fixed-container">
                <a :href="mainLink" target="_blank" rel="noopener noreferrer" class="ad-link">
                    <div class="special-area fixed-area">
                        <h2 class="fixed-title">Special Discount：50%OFF</h2>
                        <img src="@/assets/image/barking/BB.png" alt="" class="picture">
                       
                        <a :href="mainLink" target="_blank" rel="noopener noreferrer" class="btn">Get BarkBuddy Now </a>
                    </div>
                </a>
                <div class="about-author-area fixed-area">
                    <h2 class="fixed-title">About the Author</h2>
                    <img src="@/assets/image/barkingLander/author.jpg" alt="Peter Smith" class="picture">
                    <p class="name"> Kevin Roll</p>
                    <p class="desc">Our product researcher</p>
                </div>
            </div>
          </div>
      </main>
  </div>
</template>

<script>
import $ from 'jquery'
export default {
    data() {
        return {
            mainLink: 'https://www.edlwss.com/7QLQCMW/4LWQFDN/?uid=7335',
            website: 'https://www.edlwss.com/7QLQCMW/4LWQFDN/?uid=4531',
            shareBasicUrl: 'https://antibark-devices.smartchoice.reviews/',
            shareBasicTitle: '2020’s TOP 4 Anti-Barking Devices'
        }
    },
    methods: {
        shareFacebook() {
            let url = 'http://www.facebook.com/sharer/sharer.php?u='+ this.shareBasicUrl,
                title =this.shareBasicTitle,
                w = 600,
                h = 400,
                wLeft = window.screenLeft ? window.screenLeft : window.screenX,
                wTop = window.screenTop ? window.screenTop : window.screenY;
    
            let left = wLeft + (window.innerWidth / 2) - (w / 2);
            let top = wTop + (window.innerHeight / 2) - (h / 2);

            window.open(url, title, 'toolbar=no, location=no, directories=no, status=no, menubar=no, scrollbars=no, resizable=no, copyhistory=no, width=' + w + ', height=' + h + ', top=' + top + ', left=' + left);

        },
        shareTwitter() {
            let url = this.shareBasicUrl;
            let title = this.shareBasicTitle;
            window.open('http://twitter.com/share?url=' + encodeURIComponent(url) + '&text=' + encodeURIComponent(title), '', 'left=0,top=0,width=550,height=450,personalbar=0,toolbar=0,scrollbars=0,resizable=0')
        },
        shareLinkedin() {
            let url = this.shareBasicUrl,
                title = this.shareBasicTitle;
            window.open(`https://www.linkedin.com/shareArticle?mini=true&source=str&title=${title}&url=${url}`,'','left=0,top=0,width=550,height=450,personalbar=0,toolbar=0,scrollbars=0,resizable=0')
        },
        
        fixed(scrollTop,top) {
            //获取导航栏的高度
            // let navHeight = $('.header-container').outerHeight(true);
            let right = $('.barkingLander-main').offset().left;
            let footerTop = $('.footer-container').offset().top;
            //获取可视区高度
            let screenHeight = $(window).height();
            let d = $('.main-fixed-container').height();
            if (scrollTop  >= top) {

                if (scrollTop + screenHeight >= footerTop){
                    $('.main-fixed-container').css({
                        position: 'absolute',
                        top: footerTop -  screenHeight - 250 + 'px',
                        right: 0
                    })
                } else {
                    $('.main-fixed-container').css({
                        position: 'fixed',
                        top: top + 'px',
                        right: right + 'px'
                    })
                }
                
            } else if (scrollTop < top){
                $('.main-fixed-container').css({
                    position: 'absolute',
                    top: top + 'px',
                    right: 0
                })
            }
        },
        handleExecute() {
            let that = this;
            $('a').each(function () {
                let url = $(this).attr('href');
                if (url == that.mainLink) {
                    $(this).on('click',() => {
                        window.execute();
                    })
                }
            });
        }
    },
    mounted() {
        this.handleExecute();
        //获取元素距离顶部的距离
        let top = $('.main-fixed-container').position().top;
        let scrollTop = 0;
        this.fixed(scrollTop,top);
        $(window).on('scroll',() => {
            scrollTop = $(window).scrollTop();
            this.fixed(scrollTop,top)
        })

        
    },
    beforeDestroy() {
        $(window).off('scroll');

    }
}
</script>

<style lang="less" scoped>
@import url('../assets/css/BarkingLander.less');
</style>