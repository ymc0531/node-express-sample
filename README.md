#node express sample

#git clone
#git init
#.gitignore (node_modules/  .gitignore  .elasticbeanstalk/)
#eb init --platform node.js --region ap-southeast-1
#eb list (list existing env)
#eb use EXSITNG-ENV-NAME
#eb open (browse website)
#.ebextensions/nodecommand.config
#  option_settings:
#    aws:elasticbeanstalk:container:nodejs:
#      NodeCommand: "npm start"
#.ebextensions/staticfiles.config
#  option_settings:
#    aws:elasticbeanstalk:container:nodejs:staticfiles:
#      /public: /public
#git add. -> git commit -> eb deploy

#to terminate, type eb terminate
