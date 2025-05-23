+++
date = '2025-04-26 13:47:35'
draft = true
title = "Donate"
description = "Donate to Caring Valley"
show_reading_time = false
omit_header_text = false

featured_image = "/images/alex-donnachie-tvg2AeJHfbM-unsplash.webp"
featured_image_body = "/images/cvn2.jpg"
background_image_body = "/images/cvn2.jpg"
# background_color_class = "bg-light-blue"

type = 'cvn'
layout = 'page'
tags = [""]
+++

<div class="cf">
    <div class="f6 tc pl3 mw4 dn db-ns fr">
        Open on mobile
        <image src='{{<fixURL "/images/CVN-2025-Inner-Circle-DonateQR.png">}}' alt="QR code for mobile"/>
    </div>
    <p>We’re grateful for your support!</p>
    <p>You can donate to our <span class="green">Unrestricted General Fund</span> using any of the convenient methods below. If you would like to make a <span class="blue">Restricted Donation</span> please <a class="link" href='{{<fixURL "/contact" >}}'>call us directly</a> or <a href="mailto:donations@caringvalley.org" class="link">email us</a> to discuss your specific requirements.</p>
    <p>Please also vist our <a class="link dib" href='{{<fixURL "/donors" >}}'>Donor site</a> for our current needs</p>
 </div>
<div class="flex justify-around flex-wrap">
<!--more-->
    <ul class="w-30-ns flex flex-wrap items-center justify-around list pl0">
        <li>
            <button class="ba b--white br3 ph2 pv1 hover-gold bg-dark-green white"
                zeffy-form-link='https://www.zeffy.com/embed/ticketing/cvn-2025-inner-circle?modal=true'>
                Credit&nbsp;Card or Bank(ACH)
            </button>
        </li>
        <li>
            <button class="ba b--white dib br3 ph2 pv1 ma2 hover-gold bg-dark-blue white" onclick="document.location='https://www.zeffy.com/ticketing/cvn-2025-inner-circle'">
                Apple&nbsp;Pay or Google&nbsp;Pay
            </button>
        </li>
    </ul>
    <ul class="w-30-ns flex flex-wrap items-center justify-around list pl0">
        <li>
            <!-- <button class="br3 ph2 pv1 ma2 hover-white bg-gold dark-blue" onclick="document.location='https://www.paypal.com/ncp/payment/HFBP4XDQA6KSA'">
                PayPal
            </button>
            <button class="br3 ph2 pv1 ma2 hover-white bg-gold black" onclick="document.location='https://www.paypal.com/donate/?hosted_button_id=LB4F6Y74Y3P36'">
                PayPal
            </button> -->
            <button class="ba b--dark-blue br3 ph2 pv1 ma2 hover-blue bg-white dark-blue" onclick="document.location='https://www.paypal.com/donate/?hosted_button_id=AJP4243BPQNXQ'">
                PayPal
            </button>
            <a href="https://www.paypal.com/donate/?hosted_button_id=AJP4243BPQNXQ"><img src="/images/202505/pp_h_rgb.png" alt="PayPal" /></a>
            <!-- <div id="donate-button-container">
                <div id="donate-button"></div>
                <script src="https://www.paypalobjects.com/donate/sdk/donate-sdk.js" charset="UTF-8"></script>
                <script>
                    PayPal.Donation.Button({
                        env:'production',
                    hosted_button_id:'LB4F6Y74Y3P36',
                    image: {
                        src:'https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif',
                    alt:'Donate with PayPal button',
                    title:'PayPal - The safer, easier way to pay online!',
                    }
                    }).render('#donate-button');
                </script>
            </div> -->
            <div id="donate-button-container">
                <div id="donate-button"></div>
                <script src="https://www.paypalobjects.com/donate/sdk/donate-sdk.js" charset="UTF-8"></script>
                <script>
                    PayPal.Donation.Button({
                      env:'production',
                      hosted_button_id:'AJP4243BPQNXQ',
                      image: {
                        src:'/images/202505/pp_h_rgb.png',
                        alt:'Donate with PayPal button',
                        title:'PayPal - CVN General Fund',
                      }
                    }).render('#donate-button');
                </script>
            </div>
        </li>
        <li>
            <button class="ba b--white br3 ph2 pv1 ma2 hover-gray bg-light-orange white" onclick="document.location='https://www.zeffy.com/ticketing/cvn-2025-inner-circle'">Check</button>
        <li>
    </ul>
    <ul class="w-30-ns flex flex-wrap items-center justify-around list pl0">
        <li>
            <button class="br3 ph2 pv1 ma2 hover-gold bg-purple white" onclick="document.location='https://www.dafdirect.org/DAFDirect/daflink?_dafdirect_settings=MzMzMDQxMjI5XzIxMTFfYzI1MmZhMWUtOGM1Mi00OTg5LWIwYTItZDAxODBiNDcyNTM4&designatedText=R2VuZXJhbCBGdW5k&amountValue=MjY4'">DAF&nbsp;Direct</button>
        </li>
    </ul>  
</div>
<!-- <div class="tc">
  <p>OR<br>Scan to open this page on another device</P>
  <image src='{{<fixURL "/images/CVN-2025-Inner-Circle-DonateQR.png">}}'/>
</div> -->


<script src="https://zeffy-scripts.s3.ca-central-1.amazonaws.com/embed-form-script.min.js"></script>
<script src="https://www.paypal.com/sdk/js?client-id=BAAZUNwskl8tOC7pll96z540-X1nWh7o9xcDbS5XMIQkv0Y636awx6JyxyHd_It-OpgBkNaJSD5VCsugrg&components=hosted-buttons&enable-funding=venmo&currency=USD"></script>

<form action="https://www.paypal.com/donate" method="post" target="_top">
<input type="hidden" name="hosted_button_id" value="AJP4243BPQNXQ" />
<input type="image" class="w-25" src="/images/202505/pp_h_rgb.png" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>


