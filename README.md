# Project Starter Files

## Original Project

This repo was originally created by [Kevin Powell](https://kevinpowell.co) to make a personal blog site for the [Codementor](https://www.codementor.io/) DevProjects Challenge, [Create a fast and secure blog using Jamstack](https://www.codementor.io/projects/web/create-a-fast-and-secure-blog-using-jamstack-c93coupnxb).

According to Kevin at the time, "You are free to use them however you want to get started with the challenge, if you'd like to start working on creating the site without worrying about the content itself."

## File Structure

The package.json file defines the 11ty and other dependent modules used to build the site.

The `src` folder contains files so that you can get your project up and running. That folder contains:

- The Nunjucks file index.njk defines the body for the main page
- Nunjucks files in the `_includes` folder to use as a base for the different page layouts.
- Sass files for styling the pages
- 3 portfolio articles in the `portfolio` folder
- images and a logo in the `assets` folder

The articles are written in Markdown, and include Front Matter. It is possible that you will have to modify these a little if you wish to use them.

## Original Tutorial

You are not using Netlify CMS for this project - Netlify no longer supports their CMS.

With that in mind, you can [watch this video](https://youtu.be/4wD00RT6d-g) to see how Kevin used Eleventy, Netlify, and Netlify CMS to create a full-featured blog site built entirely with static files.


// Pet Rescue md //

# FurEver Project Starter Files

### Changes for FurEver

This repository has been adapted for **FurEver**, a site designed to provide resources and information about pet adoption.
- Updated design and branding for FurEver.
- Added features specific to the pet adoption theme.
- Integrated contact page, pet supplies, and pet gallery section.

## File Structure

The project is structured as follows:


### Key Directories:

- **`/src/index.njk`**: Main homepage template.
- **`/src/images/`**: Contains images and logos for the site.
- **`/src/sass/style.scss`**: Sass files for styling the pages.
- **`/src/header.njk/`**: Header file.
- **`/src/footer.njk/`**: Header file.
- **`/src/contact/index.md`**: Contact page.

### Dependencies

This project uses [Eleventy](https://www.11ty.dev/) as the static site generator. The package.json file includes all the required dependencies, including:

- **Eleventy** for templating and static site generation.
- **Sass** for styling.
- **Nunjucks** for templating.

### Running the Project

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Run `npm install` to install the necessary dependencies.
3. Run `npm run start` to build the site and start a local development server.
4. Open your browser and navigate to `http://localhost:8080` to view the site.

## Customizing the Content

The portfolio articles are written in Markdown and stored in the `/portfolio` folder. These articles include front matter, which you can modify to suit your needs (e.g., titles, dates, and content). 

Additionally, the contact form and layout can be easily customized in the `/src/contact/index.md.` template. 

### Replacing the Logo and Colors

To update the branding for **FurEver**:
- Replace the logo image in the `/src/images` folder with your own logo.
- Update the color scheme in the Sass files located in `/src/sass/style.scss`.

## Favicon and Image Credits

The following resources were used for the images and icons in this project:

- **Puppy Photo**:  
  [Side view of a rescue dog receiving affection](https://www.freepik.com/free-photo/side-view-rescue-dog-loving-affection-receives-from-woman-shelter_10295949.htm#fromView=search&page=1&position=7&uuid=6632c868-5cca-4d31-8b9e-b43fb7565d28)

- **Favicon - Paw Print with Heart**:  
  [Pet Logo Design - Paw vector animal shop business](https://www.freepik.com/free-vector/pet-logo-design-paw-vector-animal-shop-business_18246195.htm#fromView=search&page=1&position=2&uuid=75ff5f5e-e147-4079-a47b-073986c1ee3d)

- **Heart with Two Paw Prints**:  
  [Mammal paw print background with heart design vector](https://www.freepik.com/free-vector/create-mammal-paw-print-background-with-heart-design-vector_79642645.htm#fromView=search&page=3&position=31&uuid=195b6d28-16fc-4249-ae23-cce7649017af)

### Additional Pet Photos:

- **Grey and White Dog**:  
  [Shih Tzu Dog](https://pixabay.com/photos/shih-tzu-dog-pet-animal-sleeping-8287355/)

- **Brown Dog Laying Down**:  
  [Dog Laying Down](https://pixabay.com/photos/dog-animal-domestic-animal-canine-8448345/)

- **White and Grey Dog**:  
  [Malamute Dog](https://pixabay.com/photos/dog-canine-cute-pet-malamute-7330712/)

- **Yorkie Puppy**:  
  [Yorkie Puppy](https://pixabay.com/photos/puppy-yorkie-dog-pet-canine-4608266/)

- **Bulldog**:  
  [Continental Bulldog](https://pixabay.com/photos/continental-bulldog-dog-animal-pet-2437110/)

- **Black Puppy**:  
  [Black Dog](https://pixabay.com/photos/dog-puppy-pet-black-dog-animal-423398/)

- **White Dog**:  
  [White Dog](https://pixabay.com/photos/sch%C3%A4fer-dog-white-dog-dog-mammal-5767834/)

- **Grey Kitten**:  
  [European Shorthair Kitten](https://pixabay.com/photos/european-shorthair-cat-kitten-pet-8136129/)

- **Brindle Cat**:  
  [Brindle Cat](https://pixabay.com/photos/cat-feline-pet-animal-mammal-6762936/)

- **Orange Cat**:  
  [Orange Cat Kitten](https://pixabay.com/photos/cat-kitten-pet-feline-whiskers-4262034/)

## Resources

- [Eleventy Documentation](https://www.11ty.dev/docs/)
- [Sass Documentation](https://sass-lang.com/documentation)
- [Nunjucks Documentation](https://mozilla.github.io/nunjucks/)
- [Freepik](https://www.freepik.com)
- [Pixabay](https://pixabay.com)

---
