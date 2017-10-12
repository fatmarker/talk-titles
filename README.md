# Talk Titles
This is a collection of on-screen talk titles for use during congregation public meetings. Their style is meant to compliment the new song videos. The files are PNG format with a resolution of 1920 x 1080 pixels (optimized for 1080p screens).  

The images are exported from Adobe InDesign CC. The content is based on the S-99 form. Keep reading if you want to know how I compile these. I'm sure there is a better way to do this, so I'm open to suggestions. 

## Copying Text into InDesign
The fastest way I have found is by the following steps:

1) select and copy the text of the S-99
2) paste into a text editor
3) clean up the file: make sure each title is on a separate line; remove running footers 
4) save as `.csv`-file with UTF-8 encoding (see `assets/examples/talk-title-import.csv` for an example)
5) open the file in OpenOffice (easier than Excel)
6) choose a '.' (period) as your custom delimiter; set Character Set to Unicode (UTF-8); Open
7) the talk numbers and titles should be in 2 separate columns; if not, go back and try again
8) copy the talk title column
9) open the file `assets/id/talk-titles-new.indt`
10) paste into the first page; each title will create a new page

You will still have to make minor adjustments to the individual pages (slides). But at least now you don't have to individually copy 200 lines of text (or delete 200 numbers).

## Adjustments


### Centering
Text is horizontally centered by default. Vertical centering isn't as simple. Some titles are short, others are long. So a different number of lines is possible. To vertically center the text, I've provided template pages for the different numbers of lines:  
• 1L = 1-line  
• 2L = 2-line  
• 3L = 3-line  
• 4L = 4-line
  
The actualthe number of lines you need will depend on line breaks you add to each title. Do this first.

### Line Breaks

Start with the 4-line template to give you room for experimentation. Apply good typography principles. Ask someone with experience in text layout, and who also has a strong grasp of the language to assist you.  
  
Poorly laid-out text can be distracting.  

Here are a few simple rules to follow:  
- line break after commas and other punctuation
- line break after em-dashes, not before
- a preposition remains on the same line as its object

### Bold Text
Sometimes part of a title is naturally emphasised when read aloud. Use the character style "larger" to enlarge such portions of text.

## Exporting from InDesign
Export as PNG. The settings are:

### Export
All pages

### Image
• Quality: Maximum  
• Resolution (ppi): 72  
• Color Space: RGB

### Options
Anti-alias

## Translation
If you want these in another language, all the files are here for you to do that; I will only maintain the English version. Create a new fork for another language.

## Versioning
The version number is based on the date of the S-99, its language code, and builds.  
  
[S-99 year].[S-99 month].[build]

For example: 16.1.0
