# LCPN-MGH.github.io

## Edit the main page
The About page is defined under `content/_index.md` using hugo blocks. Add or remove them as required to modify the information shown

## Edit your personal page

Personal page content can be edited under content/authors/\<your_folder\>_index.md. There are predefined fields to fill out between the two --- lines, and any other information you want on your page can be added under the second --- line in markdown format.

To change your profile picture edit the avatar.jpeg file in the respective folder

## Add publications to the site

Add your paper to `publications.bib` in BibTex format. When you push the edited file, a PR will be created through GitHub actions. Accept and merge this PR for the new pages to be created under `content/publication`. 

- add a pdf (optional)
    - after the paper's folder is created and merged into `content/publication`, add a pdf file with the same name as the folder to the folder
- add an image (optional)
    - after the paper's folder is created and merged into `content/publication`, add a featured.jpg to the folder 

## Publications displayed on personal page

under `content/authors/\<your_folder\>/_index.md` add your name under the "paper_author_aliases" key as it appears on publications for it to be properly parsed and displayed. 

## Add a lab member or edit their classification

1. create a folder with a name tag
2. copy an _index.md from one of the other members
3. edit information
    - the authors field should match the folder name
4. Make sure the user_groups field matches one of the options under the user_groups field in content/people/index.md. Changing the user_groups field dictates where they'll be in the People tab
5. add a profile image and name it avatar.jpeg (can use other img formats too)

## Add News 

1. create a folder under post, and name it according to what you would like the url to be
2. add an index.md to the folder
3. define the front_matter (information between the two --- lines)
    ```
    ---
    title: <some title>
    date: <some date>
    image:
        focal_point: 'top'
    authors: [' '] # change to match one of the content/author folders if relevant
    ---
4. add any other information below the set of ---
5. add a featured.jpg to the page's folder for an image to be displayed

## TODO

1. Complete Profiles
    - Pictures
    - Overview Paragraph
    - Interests

2. Add publications to top level publications.bib

3. Update Contact Page

4. Add News/Updates for News articles

5. Select Icon for favicon

6. Images
    - Home Page image
    - Contact page image (optional, can remove)

7. Updated About blurb