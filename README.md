# that-datum
Repo of tools for you to struggle lazily with data preparation.<br>
Built with Python Tkinter. (Theme used - Azure https://github.com/rdbende/Azure-ttk-theme)<br>

![Yes](https://github.com/u-need-dropout/that-datum/blob/main/images/violet-hai.gif)

Current applications:<br>
+ Peel<br>
+ AnoDatum<br>

----

### Peel
Peel helps you to transform video into image frames.<br>

    python -m Peel

![Demo](https://github.com/u-need-dropout/that-datum/blob/main/images/Peel-demo.png)

Supported file foramts:<br>
+ avi<br>
+ mp4<br>

----

### Anota
Anota is a tool design for annotating image data.<br>

    python -m Anota

![Demo1](https://github.com/u-need-dropout/that-datum/blob/main/images/Anota-demo.png)

![Demo2](https://github.com/u-need-dropout/that-datum/blob/main/images/Anota-demo-dark.png)

![Demo3](https://github.com/u-need-dropout/that-datum/blob/main/images/Anota-demo.gif)

Supports 'loading and saving settings'.<br>
Broke size barrier.<br>

Supported annotating schemes:<br>
+ Classic (a label at a time) <br>
+ Extended (multilabels at a time) <br>
+ Hierarchical (multilabels with relation and controlled selection at a time) <br>

Current supported annotating modes:<br>
+ Bounding Box (format - [labelid, centre_x, centre_y, width, height])<br>
+ Landmark (format - [landmarkid, x, y])<br>

**Note: Everything is now Relational and in the range [0, 1] rounded to 4 decimals** <br>
**to be consistent with various image sizes.**<br>
Supported file formats:<br>
+ png<br>
+ jpg
