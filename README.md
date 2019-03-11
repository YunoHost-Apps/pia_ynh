# PIA app for YunoHost

- [Yunohost project](https://yunohost.org)
- [PIA website](https://www.cnil.fr/fr/outil-pia-telechargez-et-installez-le-logiciel-de-la-cnil)

![](https://raw.githubusercontent.com/LINCnil/pia/master/src/assets/images/pia-auth-logo.png)


[![Install PIA with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=pia)

### Installing guide

 1. App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/pia_ynh
         
        After install :
 
        1. Login in pia front
        2. Go to Settings
        3. Put your back end url
        4. Exemple Pia Front in mydomain.com/ & Pia Back is mydomain.com/pia-back

 
### Upgrade this package:

        $ sudo yunohost app upgrade pia -u https://github.com/YunoHost-Apps/pia_ynh
