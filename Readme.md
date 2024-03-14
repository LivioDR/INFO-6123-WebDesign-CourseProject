# Course Project - INFO-6123 - Web Design
### Livio Reinoso - ID 1165606
---
## Design principles
- Designed with a mobile-first approach and used CSS Media queries to change the layout for different screen sizes.
- Shared css-styles through a main reusable styles file.
- Additional form-specific styling was applied through an additional css file.
- Some images are displayed or not depending on the screen size for easier navigation and reading of the website content.
- Choosed the use of sans serif typefaces based on the competitor's websites to align with the industry branding choices.
- Added a monospace font for the footer section to differentiate it form the main content.
- The added typefaces are webfonts, with fallback common system fonts options.
- Relative units were used whenever possible to make the website compatible with different browser and screen resolutions.
- *min-width* property was used on some components to avoid text from overflowing and/or the need of scrollbars on small paragraphs.
- Used grid for the layout of the main image-text block on each page header.
- Use of flex-boxes for every other paragraph to adjust the text and images. Added classes to shift the images and text positioning from one side to the other.
- Kept the golden ration in mind when sizing the images and the paragraph linked to them.
- Applied the aspect-ratio property to avoid CLS by reserving the place for images while they load.
- Added a dynamical line-height to manage the whitespace on different browser resolutions.
---
## Accessibility strategies
- Added alt properties to all images to help blind-users and screen-reader users navigate the content.
- Added the language tag to all html pages to make sure content readers interpret the words the right way.
- Created descriptive urls to offer context to visually-impaired users that use screen readers.
- Added tabindexes to paragraphs to help with keyboard navigation.
- Used colors from opposite ends of the spectrum to help with color-blinded compatibility. Tested on the rendering module in developer tools of the browser.
- Applied labels to all input fields in the contact-us form instead of relying only on placeholder text that has low contrast.
---
## SEO strategies
- Use of a brief and descriptive title tag for each page.
- Added a customized meta description tag to every page.
- Added a keywords meta tag to every page with keywords related to the page content.
- Selected a list of keywords from both high and low-competition lists to ensure page visibility and competitivity. These keywords were searched through the use of GoogleAds Keyword Planner.
- Kept paragraphs short enough for the search engines to process them easily.
- Included keywords into the paragraphs.
- Added alt properties to all images.
---
## Image references
### Main page
- [logo.jpeg](https://i0.wp.com/1.bp.blogspot.com/-s4No_YP009c/YDYabJplR0I/AAAAAAAHpKk/i9EgVqpW12smIm-TuWvacgddx6JWNLVswCLcBGAsYHQ/s1600/NU_Behance_MIL-01.jpg?w=640&ssl=1)
- [catering-home-01.jpeg](https://www.caterino.es/images/menu-empanadas-9c19336b.jpg)
- [catering-friends.jpeg](https://cateringargentino.es/wp-content/uploads/2023/05/catering-argentino-7.jpg)
- [catering-party-01.jpg](https://media-cdn.tripadvisor.com/media/photo-s/03/82/19/2c/el-argentino.jpg)
- [catering-party-02.jpeg](https://pizzabaypizzaparty.com.ar/wp-content/uploads/2018/08/01.jpg)
- [catering-dish-01.jpeg](https://as2.ftcdn.net/v2/jpg/04/80/90/03/1000_F_480900365_1UPsFJvlF72ynefeHKy6TjCnrTR8wQ4W.jpg)

### Appetizers
- [Appetizers-main.jpeg](https://images.squarespace-cdn.com/content/v1/579bd3a2197aea7c6b7aa2e2/1511908203601-9D5TMYW6L011PW45RNZ4/Mouth-Watering-Argentinian-Appetizers-san-diego.jpg?format=2500w)
- [choripan.png](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSO0kveseCOQ7j0izEBQ946x6F1ltg0tlRIVrnuVW3ediPq7siY)
- [empanadas.jpg](https://assets.elgourmet.com/wp-content/uploads/2023/03/cover_fpa6sn8vqc_empanadas.jpg)
- [matambre-arrollado-resized.jpg](https://www.curiouscuisiniere.com/wp-content/uploads/2017/11/Matambre-Arrolado-Argentinian-Rolled-Stuffed-Flank-Steak-4457.21.jpg.webp)
- [provoleta.jpeg](https://cdn.kiwilimon.com/recetaimagen/21771/11560.jpg)
- [sandwichMiga.jpeg](https://www.clarin.com/img/2021/08/06/M4wbnpEIC_720x0__1.jpg)

### Main courses
- [main-courses-mainImg.jpeg](https://blog.amigofoods.com/wp-content/uploads/2020/08/argentinian-milanesa.jpg)
- [fugazzeta.jpg](https://www.thermorecetas.com/wp-content/uploads/2022/04/DSC_4341-2-1024x683.jpg)
- [locro.jpg](https://www.casacomida.com/wp-content/uploads/2016/03/Locro.jpg)
- [matambre-a-la-pizza.jpg](https://www.clarin.com/img/2022/11/25/tR-l3EmRl_1256x620__2.jpg#1669400323977)
- [milanesa-napolitana.jpeg](https://preview.redd.it/mo3bavlc26n51.jpg?width=480&format=pjpg&auto=webp&s=7a4229ba6bfef685ff6fd478e0d96cd8cce4ae6a)

### Desserts
- [desserts-main.jpeg](https://cdn0.casamientos.com.ar/article-real-wedding/563/3_2/1920/jpg/295289.webp)
- [alfajor.jpeg](https://infobrisas-s3.cdn.net.ar/s3i233/2024/01/infobrisas/images/46/54/465437_45e77ada0c66957f5daab530509e2cf42b5102c218cb2e3df76c2a0d94244c73/md.webp)
- [flan.jpg](https://pxccdn.ciudadano.news/ciudadano/062021/1623024258531/flan.webp?cw=984&ch=553&extw=jpg)
- [panqueques.jpg](https://imag.bonviveur.com/panqueques.webp)
- [pastelitos.jpeg](https://www.tastingtable.com/img/gallery/the-flaky-pastry-thats-eaten-to-celebrate-argentinas-independence/intro-1669654841.webp)

### Contact Us
- [contact-us-banner.avif](https://koa.com/blog/images/group-camping-food.jpg?preset=blogPhoto)
- [contactus-side.jpg](https://www.taketwotapas.com/wp-content/uploads/2021/07/Beef-Empanadas-Take-Two-Tapas-15.jpg.webp)