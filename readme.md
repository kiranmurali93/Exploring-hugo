# A BASIC BLOG USING HUGO
---
# Materials
### -[Hugo Git repo](https://github.com/gohugoio/hugo)

### -[Template_used](https://github.com/alexandrevicenzi/soho)

# Settingup hugo 

- ## [Hugo installation](https://gohugo.io/getting-started/installing/)

# Creating a project

To create a project

- open terminal and use the command

        hugo new site projectname

# Running a hugo server

- after creating a hugo site
    locate the file by "cd filename"

    And use the command
        
        hugo server

- Now since the server is running we can see a blank page.


# use a template

- Select a template from [Hugo template](https://gohugo.io/templates/)
- after selecting go to themes by
        
        cd themes

- Clone the repo using
    
        git clone ""
    For example the theme i have use here is [soho](https://themes.gohugo.io/soho/)
    
    To clone the theme 
            
        git clone https://github.com/alexandrevicenzi/soho.git


# Editing the template

Now for configuring the theme
    
  - go to config.toml and add
        
        theme="theme_name"

# create a post

To create a post

    hugo new post/post_name
