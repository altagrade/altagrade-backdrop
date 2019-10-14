# AltaGrade development environment for Backdrop
This repository helps to quickly get the latest development branch of Backdrop running on Docksal.

1. Install Docksal per https://docksal.io/installation if you don't already have it.
2. Go to your ~/Projects folder and clone the repository with:

```
git clone git@github.com:AlexShapka/altagrade-backdrop.git your-new-project
```

3. Change working directory and run the initiation script:

```
cd your-new-project
./init
```

4. Go to http://your-new-project.docksal/user, login with username `admin`, password `admin` and start working with your website.

5. MailHog located is a cool way of catching all messages sent out from your website while developing it. To test it just enable the contact module with `drush en contact`, send a test message using the http://musa.docksal/contact form and check you MailHog at http://mail.your-new-project.docksal.

6. phpMyAdmin is located at http://pma.your-new-project.docksal.

# Trobleshooting

Report all errors and issues on https://github.com/AlexShapka/altagrade-backdrop/issues.
