    - run:
          name: deploy
          command: |    
            npm install
            pm2 stop default
            pm2 start npm -- start