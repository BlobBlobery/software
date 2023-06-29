# software

# Tips

Lars:

Christian:

<a href="https://www.buymeacoffee.com/c.mz"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a salad&emoji=🥗&slug=c.mz&button_colour=40DCA5&font_colour=ffffff&font_family=Cookie&outline_colour=000000&coffee_colour=FFDD00" /></a>

<a href="https://www.paypal.com/paypalme/christianmueller659">
  <img src="https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png" alt="PayPal me a salad" />
</a>


<body>
 <div id="paypal-donate-button-container"></div>

  <script>
   PayPal.Donation.Button({
       env: 'production',
       hosted_button_id: 'YOUR_LIVE_HOSTED_BUTTON_ID',
       // business: 'YOUR_LIVE_EMAIL_OR_PAYERID',
       image: {
           src: 'https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif',
           title: 'PayPal - The safer, easier way to pay online!',
           alt: 'Donate with PayPal button'
       },
       onComplete: function (params) {
           // Your onComplete handler
       },
   }).render('#paypal-donate-button-container');
</script>
</body>
