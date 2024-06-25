# Dzmitry Kulevich

## Senior QA Automation Engineer

## Contact information:
 
Email: [kulevich.dzmitry@gmail.com](mailto:kulevich.dzmitry@gmail.com)\
Linkedin: [Dzmitry Kulevich](https://www.linkedin.com/in/dzmitry-kulevich/)\
Telegram: [@selestrel](https://t.me/selestrel)
***

## Professional Summary

Experienced QA Automation Engineer with over 6 years of proven expertise in developing robust test frameworks, creating and executing automated test scripts, and mentoring team members. Adept at operating within the Scrum framework, I have successfully monitored bug resolutions and provided valuable QA perspectives to enhance overall software quality.

My dedication to excellence is showcased through my proactive approach to anticipating and addressing potential issues, aiding developers in mitigating future challenges. With a strong foundation in quality assurance, I am now poised to transition my career to a JavaScript Software Developer role.

## Skills and Proficiency

+ CSS
+ HTML
+ JavaScript
+ SQL
    + PostgreSQL
    + MySQL
    + Oracle
+ Java
+ Spring
+ Maven
+ Selenium
+ Jira

## Code example:

**Count the smiley faces! KATA from CodeWars:** Given an array (arr) as an argument complete the function countSmileys that should return the total number of smiling faces.
Rules for a smiling face:
Each smiley face must contain a valid pair of eyes. Eyes can be marked as *:* or *;*
A smiley face can have a nose but it does not have to. Valid characters for a nose are *-* or *~*
Every smiling face must have a smiling mouth that should be marked with either *)* or *D*
No additional characters are allowed except for those mentioned.
Valid smiley face examples: *:) :D ;-D :~)*
Invalid smiley faces: *;( :> :} :]*

```
function countSmileys(arr) {
    return arr.filter(el => el.match(/[:;]{1}[-~]{0,1}[D\)]{1}/)).length;
}
```
