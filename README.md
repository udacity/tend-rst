# TEND Additional Resources Core Files

## What is this?

Hello world! This repository stores the basic files that make up Udacity's TEND extra resource page. Changing the actual page takes several steps, and the first is changing the RST files in this folder.

## What are the steps for updating the TEND resources?

1. Edit the RST files in this repository. In this step, you'll be changing the text you'll actually see on the web pages. If you're familar with Git already, you can download this repo, locally make changes, and push normally. Otherwise:

  1. Find the RST file for the page you'd like to edit. For example, if you want to edit the "Learn about Your Industry" page, you'll be editing "learn_about_your_industry.rst".

  2. When you click on the file name, you should see some styled text, similar to how it appears on the website. Github actually as compiler for RST and similar files, so it's automatically converting all the symbols to formatting. This is **NOT** what the file actually looks like! To see the actual file, click the little pencil icon in the top right corner of this section.

  3. You should be able to see the raw file now, it all of it's bizarre glory. Now you can go ahead and make changes! For text changes you can just edit the words you see. If you're adding new sections, links, or other things that require formatting, you should poke around the other RST files to see what the convention is. I have some conventions listed below to save you time!

  4. Once you're done, you should see a box below called "Commit changes". A "commit" is essentially just an update to the code base. In the top text box, describe the type of change you made (and include the name of the file). For example:

    - Fixed a typo? --> "Fixed typo in design section of learn...industry.rst"
    - Added new resources? --> "Added new links to job_boards.rst"

  5. You can add a longer description in the "Add an optional extended description..." box, but it's definitely preferable to just add one clear line in the top text box.

  6. Leave the "Commit directly to the master branch" option checked.

  7. When you're done, click the green "Commit changes" button. Congrats!

2. Updating the RST files does not change the actual live website. When the RST files are updated, just ping Brynn on Slack for now, and she'll do the next steps for you!

## What are RST files?

RST stands for reStructuredText. It's essentially a text file (with a few complications and extra characters), but after running it through a certain type of compiler program it can be turned into a website with proper formatting. For example, if you write something like this, you'll see a big heading on your website:

```
******
Header
******
```

The asterisks around a word signals to the compiler that is should make the text bigger and bolder when it's turned into a website. To see all of the conventions for RST files, you should poke around other files in this repository and learn some of the patterns.

## RST Conventions

#### Headings

```
***********
Page Header
***********
```
This is the biggest, dark blue heading. It's exclusively for page titles.

```
==============
Section Header
==============
```

The section header is the second-largest, and will appear as a lighter blue on the website.

```
------------------
Sub-Section Header
------------------
```

This smallest header will appear black on the website.

#### Links

Links will appear in this format: 

```
`Udacity <http://www.udacity.com/>`_
```

Links used in-line will appear light blue, but not bold. To create a list of bold links, put the link on it's own line and put the descriptive text below it indented by four spaces like so:

```
`Udacity <http://www.udacity.com/>`_
    Best learning resource EVER!
```

 # Archival Note 
 This repository is deprecated; therefore, we are going to archive it. However, learners will be able to fork it to their personal Github account but cannot submit PRs to this repository. If you have any issues or suggestions to make, feel free to: 
- Utilize the https://knowledge.udacity.com/ forum to seek help on content-specific issues. 
- Submit a support ticket along with the link to your forked repository if (learners are) blocked for other reasons. Here are the links for the [retail consumers](https://udacity.zendesk.com/hc/en-us/requests/new) and [enterprise learners](https://udacityenterprise.zendesk.com/hc/en-us/requests/new?ticket_form_id=360000279131).