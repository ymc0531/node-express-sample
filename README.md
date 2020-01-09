#node express sample

git clone

git init

git rm --cached node-express-sample

.gitignore (node_modules/  .gitignore  .elasticbeanstalk/)

eb init --platform node.js --region ap-southeast-1

eb list (list existing env)

eb use EXSITNG-ENV-NAME

eb open (browse website)

.ebextensions/nodecommand.config

option_settings: \n
  
aws:elasticbeanstalk:container:nodejs: \n
    
NodeCommand: "npm start"

.ebextensions/staticfiles.config

option_settings: \n
  
aws:elasticbeanstalk:container:nodejs:staticfiles: \n
    
/public: /public

git add. -> git commit -> eb deploy

to terminate, type eb terminate
