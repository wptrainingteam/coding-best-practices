# Coding Best Practices

## Description

Teach WordPress Coding Best Practise. Focus on good WordPress code, with semantic markup and WordPress. The principles in the lesson are valid for all code. As a sample the class will code a plugin with a "_Hello World_" shortcode. The plugins can display an image, and the text strings will be translation ready.  

## Prerequisite Skills

The intended target group is undergraduates, with:

*   Basic knowledge of HTML5.
*   CSS3.
*   JavaScript, and
*   PHP

The students should have at least some knowledge about the topics listed above. They don't have to know each and every detail.

## Objectives

*   How to plan the markup for a custom WordPress loop?
*   How to add the WordPress PHP snippets, like the_author() etc.
*   How to comment on your markup and your PHP.
*   Learn to write readable, and beautiful code.
*   Link correctly to images.
*   Make translation ready text strings.
*   Knowledge of best practice.

## Assets

A bulleted list of linked files/materials the instructor needs to teach the module.

*   [Links to download files](#)
*   ( Files on github, coming here )

More about WordPress coding standards:

*   [WordPress Coding Standards](https://codex.wordpress.org/WordPress_Coding_Standards). ( A behemoth of information )

## Screening Questions

In order to complete this lesson you need:

*   A local server with Apache, MySQL, and PHP ( read: Xampp, Wamp, Mamp, Lamp or similar )
*   Is your server up and running? ( try: [http://localhost/](http://localhost/) )
*   Open WordPress in a browser: http://localhost/wordpress ( or whatever localhost address you've used )

If WordPress is up and running it's ok. If not:

1.  Check that Xampp or similar is on.
2.  Check that Apache is running.
3.  Check that MySQL is running.
4.  Try to load [http://localhost/wordpress](http://localhost/wordpress)  again.

Mac, Unix and Linux users should make sure, that the **wp-config** folder is read-and-writable for _everyone. _Otherwise you may not be able to edit your files, or install themes and plugins. I you don't know whether you can read / write or not, try this: open ../wp-config/plugins/ and create a file, give it the name z.txt or similar. If you're allowed to create the file, it's ok. Since you probably don't want the file any more, delete it again. If you can't create the file, check the folder settings.

## Teacher Notes

A bulleted list of any handy tips or information for the instructor.

*   In general students with Mac computers have difficulties wih read-write-permissions.
*   Go to the students with a Mac, and make sure that the folder **wp-config** is readable and writable.
*   Also make sure that all the permissions are redundant ( i.e. the permissions must be valid for all files and folders inside wp-config ).

## Hands-on Walkthrough

The lesson, written in script form with screenshots and live demo instructions to be used by the instructor in a live classroom/workshop setting.

### Section Heading for Walkthrough

You will likely need to break down the walkthrough into sections.

## Exercises

These are short or specific activities that test an understand and help you practice certain components of the lesson. They should not be fully scripted exercises, but rather something that you would do on your own. For example, you can create an exercise based on one step of the hands-on walkthrough. **Exercise name** Short description of what the exercise does and what skills or knowledge it reinforces.

*   Short point or step of the exercise
*   And another.

## Quiz

A short quiz for students to evaluate their retention of the material presented. **Write out the question.**

1.  Option
2.  Option
3.  Option
4.  Option

**Answer:** 3\. Correct answer

## Quiz

What is the best way to use **else if** condition.
1.  else if
2.  if else
3.  elseif

**Answer:** 3\. Correct answer because **else if** is not compatible with the colon syntax for **if|elseif** blocks. For this reason, use **elseif** for conditionals. 

 **How to create dynamic image path in WordPress theme files?**

1. <?php bloginfo('template_url'); ?>
2.  <?php echo site_url(); ?>
3.  <?php get_stylesheet_directory_uri(); ?>


**Answer:** 1\. <?php bloginfo('template_url'); ?>


