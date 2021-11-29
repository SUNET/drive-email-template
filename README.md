# E-Mail Template for Sunet Drive
In order to customize e-mails sent by Sunet Drive, a small custom app has to be deployed. The apps here are based on [Customized email templates](https://portal.nextcloud.com/article/customized-email-templates-29.html).
To manually deploy the respective e-mail template:
1. Copy the respective folder to <nextcloud>/custom_apps/<emailapp>
2. Add parameter to config.php. E.g., `'mail_template_class' => 'OCA\KauEmailTemplate\EMailTemplate',` 
3. Activate the app under Apps
