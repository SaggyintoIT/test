<html>
  <body>
    <script type='text/javascript'>
    function initEmbeddedMessaging() {
        try {
            embeddedservice_bootstrap.settings.language = 'en_US'; 

            embeddedservice_bootstrap.init(
                '00DdM000009e2vZ',
                'aiqube_tech',
                'https://sad-e-dev-ed.develop.my.site.com/ESWaiqubetech1723128692907',
                {
                    scrt2URL: 'https://sad-e-dev-ed.develop.my.salesforce-scrt.com'
                }
            );
        } catch (err) {
            console.error('Error loading Embedded Messaging: ', err);
        }
    };
</script>
<script type='text/javascript' src='https://sad-e-dev-ed.develop.my.site.com/ESWaiqubetech1723128692907/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
