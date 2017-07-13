# ResumeInAcademic
a resume created by Hugo in academic theme

## Getting Started
1.install Hugo

    brew update
    brew install hugo 

2.add Hugo Theme,you can find more themes in [themes](https://themes.gohugo.io)

    cd ~/site/themes
    git clone https://github.com/gcushen/hugo-academic.git

3.start Hugo Server,this site will show on http://localhost:1313,as the commond's log

    cd ~/site
    hugo server -w

4.create html,this commond will create a file named "public" in ~/site,include html and so on
    
    hugo

5.share your site by netlify

    cd ~/site
    npm install netlify-cli -g
    cd ~/site/public
    netlify deploy
