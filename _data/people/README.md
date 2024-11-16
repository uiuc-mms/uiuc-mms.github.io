# How to Add Yourself

Adding yourself to the website is very easy. There are only three steps:

1. Upload a picture of yourself, must be .jpg or .png, to the imgs/people directory
2. Add a firstlast.md file to \_data/people/bios directory detailing who you are, and the research you do. This can be as detailed as you want! Please include Pictures of your hobbies / research interests!!
3. Add yourself to the people.yml file in \_data/people directory!

# Example

When ading yourself to the .yml file, please use the following template:

```
 - name: First Last
   pronouns: first/third
   pic: /imgs/people/yourpic.png
   dates: startyear-present
   role: Your Role
   url: /_data/people/bios/yourbio.md
   social:
   - url: https://github.com/yourgithub
     icon: github-alt
     name: Github
   - url: mailto:youremail@email.com
     icon: envelope-o
     name: Email
``` 

If you are unfamiliar with Markdown file syntax, or simply want to see the compiled version side-by-side with your code, HackMD is very good tool!


