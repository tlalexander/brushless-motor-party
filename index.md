## Let's Have Brushless Motor Party

Brushless motors are one type of electric motor that work great for robotics! They are very powerful and can be precisely controlled from software.
This page is intended to explain to a beginner how and where to get started using these motors in projects.

### Prologue: Brushed Motors and Steppers

Whoa there! Before you go and spend $200 on a brushless motor and controller combination, let's make sure all that expense is worth it. A brushed motor is simpler than a brushless motor. The motor itself is cheaper, and they are also easier to control which makes their motor controllers cheaper. They have less power output than a brushless motor. Many projects will work well with brushed motors, and the expense of brushless motors is not necessary. Look up "12v DC motor" or "12v DC gearmotor" on your preferred web store and see what comes up. Amazon and Aliexpress are two places to look. You will need an "H-Bridge" controller to control the motor in both directions with software. If you only need the motor to move in one direction, you only need a power source and a switch, either a mechanical switch or a MOSFET hooked up to a controller. This might be Arduino or Raspbery Pi. To control speed or position of the motor, see Encoders this page. To control motor torque, find a way to control the current, possibly with a current sensor and PWM on the motor.


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tlalexander/brushless-motor-party/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
