<html lang="en">
<head>
	<title>SFDC MIAW - Wed Demo</title>
	<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
</head>
<body >
	Welcome SFDC MIAW - Wed Demo
	<script type='text/javascript'>
		function initEmbeddedMessaging() {
			try {
				console.log('initEmbeddedMessaging');
				embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
				
				console.log('initEmbeddedMessaging', 'embeddedservice_bootstrap');
				embeddedservice_bootstrap.init(
					'00D2w000007Ph69',
					'rxop__MIAW_Github',
					'https://crmified-dk-dev-ed.my.site.com/ESWMIAWGithub1717401177483',
					{
						scrt2URL: 'https://crmified-dk-dev-ed.my.salesforce-scrt.com'
					}
				);
				console.log('initEmbeddedMessaging','embeddedservice_bootstrap','done');
			} catch (err) {
				console.error('Error loading Embedded Messaging: ', err);
			}
		};
	</script>
	<script type='text/javascript' src='https://crmified-dk-dev-ed.my.site.com/ESWMIAWGithub1717401177483/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>


