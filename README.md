# Limesurvey-RCE
**LimeSurvey Authenticated RCE**
Proof of Concept:
1. Create your files (config.xml and php reverse shell files)
2. Create archive with these files
3. Login with credentials
4. Go Configuration -> Plugins -> Upload & Install
5. Choose your zipped file
6. Upload
7. Install
8. Activate plugin
9. Start your listener
10. Go url+{upload/plugins/#Name/#Shell_file_name}
11. Get reverse shell :shipit:

### ***You can use exploit.py for automatic exploitation.***
#### Usage: python exploit.py URL username password port
#### Example Usage: python exploit.py http://192.26.26.128/limesurvey admin password 80
