+++
date = '2025-04-26 13:47:35'
draft = false
title = "General Donation "
description = "Donate to CVN General Fund"
show_reading_time = false
omit_header_text = false
# read_more_copy = "Other Payment Methods"
read_more_copy = "Make a General Donation"
weight = 2

featured_image = "202503/alex-donnachie-tvg2AeJHfbM-unsplash.webp"
featured_image_body = "202507/CVN General Donation with Flowers.webp"
# background_image_body = "/images/cvn2.jpg"
# background_color_class = "bg-light-blue"
# body_classes = "Montserrat"

type = 'cvn'
layout = 'page'
tags = [""]
+++

<div class="cf">
  <div class="f6 tc pl3 mw4 dn db-ns fr">
      Open on mobile
      <image src='{{<fixURL "/images/202505/CVN Donate General Fund QR.png">}}' alt="QR code for mobile"/>
  </div>
  <p>We’re grateful for your support!</p>
  <p>You can donate to our <span class="green">Unrestricted General Fund</span> using any of the convenient methods below. If you would like to make a <span class="blue">Restricted Donation</span> please <a class="link blue" href='{{<fixURL "/contact" >}}'>call</a> or <a href="mailto:donations@caringvalley.org" class="link blue">email</a> to discuss your specific requirements.</p>
  <p>Please also vist our <a class="link blue" href='{{<fixURL "/donors" >}}'>Donor site</a> to see our current needs.</p>
</div>
<!--more-->
<div class="flex justify-around items-stretch bg-white mb3 pv3">
      <button class="w-60 ba b--white br3 ph2 pv1 hover-gold bg-dark-green white"
        zeffy-form-link="https://www.zeffy.com/embed/donation-form/cvn-general-fund?modal=true">
        Credit&nbsp;Card OR Bank&nbsp;(eCheck)
      </button>
      <p class="b f6 dark-blue">Preferred<br>No fees</p>
</div>
<div class="flex justify-around justify-between-ns items-stretch flex-wrap">
    <div class="w-30-ns flex flex-column item-center justify-around bg-white ph2 tc pb3 mb3" style="min-height:175px">
      <a href="https://www.zeffy.com/donation-form/cvn-general-fund" class="flex item-center justify-center br3 pv1 ph2 hover-bg-near-white bg-white">
        <img class="mw4" src='{{<fixURL "/images/202505/ApplePay-GooglePay.svg">}}' alt="Apple Pay" />
      </a>
      <p class="b f6 dark-blue mv0 flex flex-column justify-end">No fees<br>5~10 min<br>Less than $1000</p>
    </div>
    <div class="w-35-ns flex flex-column items-stretch justify-around bg-white ph2 tc p3 mb3" style="min-height:200px">
      <!-- <a class="link flex items-stretch justify-center ba b--white br3 ph2 hover-gray bg-light-orange white" href="https://www.zeffy.com/ticketing/cvn-2025-inner-circle">
        Mail Check
      </a> -->
      <button class="link flex items-stretch justify-center ba b--white br3 ph2 hover-gray bg-light-orange white" onclick="document.getElementById('FullScreenOverlay').style.display = 'block'; document.getElementById('MailCheck').style.display = 'block';">
        Mail Check
      </button>
       <a class="link flex items-stretch justify-center br3 ph2 hover-gold bg-dark-blue white" href="https://paypal.com/us/fundraiser/charity/5519072">
        PayPal&nbsp;Giving&nbsp;Fund
      </a>
      <!-- <a class="link flex items-stretch justify-center br3 ph2 hover-gold bg-purple white" href="https://www.dafdirect.org/DAFDirect/daflink?_dafdirect_settings=MzMzMDQxMjI5XzIxMTFfYzI1MmZhMWUtOGM1Mi00OTg5LWIwYTItZDAxODBiNDcyNTM4&designatedText=R2VuZXJhbCBGdW5k&amountValue=MjY4">
        DAF&nbsp;Direct
      </a> -->
      <button class="flex items-stretch justify-center br3 ph2 hover-gold bg-purple white" onclick="document.getElementById('FullScreenOverlay').style.display = 'block'; document.getElementById('dafdirectdiv').style.display = 'block';">
        Donor Advised Fund
      </button>
      <p class="b f6 dark-blue mv0 flex flex-column justify-end">No Fees<br>2~4 weeks</p>
    </div>  
    <div class="w-30-ns flex flex-column items-stretch justify-around bg-white ph2 tc pb3 mb3">
      <a href="https://www.paypal.com/donate/?hosted_button_id=CGL6E4ZY9KSKE" class="flex items-stretch justify-center br3 pa2 hover-bg-near-white bg-white"><img class="mw4" src='{{< fixURL "/images/202505/pp_h_rgb.png" >}}' alt="PayPal" /></a>
      <p class="b f6 dark-blue flex flex-column justify-end">2~3% in fees<br>1~2 days</p>
    </div>
</div>

<script src="https://zeffy-scripts.s3.ca-central-1.amazonaws.com/embed-form-script.min.js"></script>
<script src="https://www.paypal.com/sdk/js?client-id=BAAZUNwskl8tOC7pll96z540-X1nWh7o9xcDbS5XMIQkv0Y636awx6JyxyHd_It-OpgBkNaJSD5VCsugrg&components=hosted-buttons&enable-funding=venmo&currency=USD"></script>


<style>#dafdirectdiv {
  display: none;
  position: fixed;
  top: 50%;
  left: 50%;
  min-width: 300px !important;
  transform: translate(-50%,-50%);
  z-index: 1000;
  background-color: rgba(0, 0, 0, .6);}
</style>
<script type ="text/javascript">_dafdirect_hide_button="no"; _dafdirect_settings="333041229_2000_09d23139-57e8-4cf5-b667-e4d0b3f93876";</script>
<script type = "text/javascript" src = "http://dafdirect.org/ddirect/dafdirect4.js"></script>

<!-- css -->
<style>
.modal {
  display: none;
  position: fixed;
  top: 50%;
  left: 50%;
  width: 90vw;
  transform: translate(-50%,-50%);
  z-index: 1000;
  max-height: 80vh;
  overflow-y: auto;
}
</style>

<!-- Full Screen Overlay -->
<div id="FullScreenOverlay" style="display:none; position:fixed; top:0; left:0; width:100vw; height:100vh; background:rgba(0,0,0,0.7); z-index:999;"></div>

<!-- Mail check -->
<div id="MailCheck" class="modal ba0 br3 ph4 pv2 bg-white f5">
<button onclick="document.getElementById('MailCheck').style.display = 'none'; document.getElementById('FullScreenOverlay').style.display = 'none';" style="position:absolute; top:1rem; right:1rem;">&times;</button>
  <p>
    This donation will accepted into our <span class="b">Unrestricted General Fund</span>.<br>
    We incur no fees to accept checks, however it takes around 1-2 weeks to process.
  </p>
  <ol>
    <li>Make your check out to <span class="b blue">CARING VALLEY NONPROFIT</span>.</li>
    <li>Enter your <span class="b green">email id</span> the memo section of your check. We use your email id to send your donation reciept and/or to contact you in case of any issues/questions.</li>
    <li>Mail your check to:
      <div class="pl2">
        CARING VALLEY NONPROFIT<br>
        ATTN: Donation Processing<br>
        39899 Balentine Dr, Ste 136<br>
        Newark, CA 94560
      </div>
    </li>
    <li>Send an email to <a class="link red" href="mailto:donations@caringvalley.org">donations@caringvalley.org</a> listing the check number and amount.</li>
  </ol>
</div>

<script>
  // const DafModal = document.getElementById ("dafdirectdiv");
  const FullScreenOverlay = document.getElementById ("FullScreenOverlay");
  const MailCheckModal = document.getElementById ("MailCheck");
  window.onclick = function(event) {
    if (event.target === FullScreenOverlay) {
      FullScreenOverlay.style.display = "none";
      MailCheckModal.style.display = "none";
      document.getElementById("dafdirectdiv").style.display = "none";
    }
  }
</script>

