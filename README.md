# LCPN-MGH.github.io

## Edit the main page


## Edit your personal page

Personal page content can be edited under content/authors/\<your_folder\>_index.md. There are predefined fields to fill out between the two --- lines, and any other information you want on your page can be added under the second --- line in markdown format.

To change your profile picture edit the avatar.jpeg file in the respective folder

## Add publications to the site

Add your paper to `publications.bib` in BibTex format. When you push the edited file, a PR will be created through GitHub actions. Accept and merge this PR for the new pages to be created under `content/publication`. If relevant you can add an image to the publications folder, or add a pdf and it will be linked on the site.

## Publications displayed on personal page

under content/authors/\<your_folder\>/_index.md add your name under the "paper_author_aliases" key as it appears on publications for it to be properly parsed and displayed. 

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

# The Lab for Neuroimaging and Neuroinformatics (LNN) @ UCPH

This is the official website for the Lab for Neuroimaging and Neuroinformatics (LNN) at the University of Copenhagen (UCPH). Below are instructions for configuring and updating the site.

## Configuration

Most of the configuration is managed in the [`config/_default`](config/_default) directory.

- The **baseURL and title** are defined in `hugo.yaml`.
- The **navigation bar** is specified in `menu.yaml`.
- The **weight parameter** determines the order in which links appear in the navigation bar.

For more details on configuring Hugo, refer to the [Hugo documentation](https://gohugo.io/documentation/).

## How to Add Content

### Updating the Main Page
The main page content is stored in [`content/_index.md`](content/_index.md) and is structured in blocks. You can modify this file to update the homepage text or layout.

For advanced customization, refer to the [Hugo documentation on content organization](https://gohugo.io/content-management/organization/).

### Adding Lab Members
Lab members are listed in the [`content/authors`](content/authors) directory. Each member has their own folder containing:
- An `_index.md` file with their profile details.
- An `avatar.jpg` for their profile picture.

To add a new member, create a new subdirectory with their name under `content/authors/` and include these two files.

### Managing Publications
New publications are automatically processed using **GitHub Actions**. To add a new publication:
1. Add the BibTeX entry for your latest publication to `publications.bib`.
2. Submit a **Pull Request** with the updated `publications.bib` file.
3. Once merged, GitHub Actions will generate a new directory under [`content/publication`](content/publication).