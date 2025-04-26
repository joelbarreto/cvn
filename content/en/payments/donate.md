+++
date = '2025-04-26 13:47:35'
draft = false
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
    <div class="pr3 mw4 dn db-ns fr">
        <!-- <p>Open on mobile</P> -->
        <image src='{{<fixURL "/images/CVN-2025-Inner-Circle-DonateQR.png">}}'/>
    </div>
    <p>We’re grateful for your support!<br>You can donate using any of these convenient methods:</p>
</div>
<div class="tc flex justify-start-ns justify-around">
    <ul class="list pl0">
    <!--more-->
        <li class="purple b">
            <button class="br3 ph2 pv1 hover-gold bg-dark-green white"
                zeffy-form-link='https://www.zeffy.com/embed/ticketing/cvn-2025-inner-circle?modal=true'>
                Credit&nbsp;Card or Bank(ACH)
            </button>
        </li>
        <li class="purple b">
            <button class="br3 ph2 pv1 ma2 hover-gold bg-dark-blue white" onclick="document.location='https://www.zeffy.com/ticketing/cvn-2025-inner-circle'">
                Apple&nbsp;Pay or Google&nbsp;Pay
            </button>
        </li>
        <li class="purple b">
            <button class="br3 ph2 pv1 ma2 hover-white bg-gold dark-blue" onclick="document.location='https://www.paypal.com/ncp/payment/HFBP4XDQA6KSA'">
                PayPaL
            </button>
            <button class="br3 ph2 pv1 ma2 hover-white bg-gold black" onclick="document.location='https://www.paypal.com/donate/?hosted_button_id=LB4F6Y74Y3P36'">
                PayPaL
            </button>
            <div id="donate-button-container">
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
            </div>
        </li>
        <li class="purple b">
            <button class="br3 ph2 pv1 ma2 hover-white bg-purple white" onclick="document.location='https://www.zeffy.com/ticketing/cvn-2025-inner-circle'">
                Check
            </button>
        </li>
    </ul>  
</div>

<script src="https://zeffy-scripts.s3.ca-central-1.amazonaws.com/embed-form-script.min.js"></script>
<script src="https://www.paypal.com/sdk/js?client-id=BAAZUNwskl8tOC7pll96z540-X1nWh7o9xcDbS5XMIQkv0Y636awx6JyxyHd_It-OpgBkNaJSD5VCsugrg&components=hosted-buttons&enable-funding=venmo&currency=USD"></script>
