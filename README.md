# 0x0B. Implement a design with bootstrap

In this project, you will implement 3 web pages with Bootstrap. You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.

Here the final result:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3c71cc99d2fc1c12a3d3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7540c3f13441e7eab73f7e7c2e3c2c9c9c14715056ee0e2b479c7acac6e63d6b)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/623/Archive.zip "here")

### Requirements

-   You have to use Bootstrap
-   Your  `styles.css`  must be as small as you can -  **you must use as much as you can Bootstrap classes**

### Imports

For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS

```
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Coiny&display=swap" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

```

## Tasks

### 0. Read and be familiar with Figma

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Create an account in  [Figma](https://intranet.hbtn.io/rltoken/0OS4ME4Kjnw0I82IVkkoSw "Figma")  and open these files:

-   [Homepage](https://intranet.hbtn.io/rltoken/RLej4Ua6W3EmDh7UCwGTzQ "Homepage")  -  [fig file](https://intranet.hbtn.io/rltoken/1ZTxYF-usvxpIjj44YYcyw "fig file")
-   [Pricing](https://intranet.hbtn.io/rltoken/xQCL77_ePGWntUAe4T7ebQ "Pricing")  -  [fig file](https://intranet.hbtn.io/rltoken/AdJ6ZyZrG90gRNAI5bt_lA "fig file")
-   [Courses](https://intranet.hbtn.io/rltoken/__3w9ryapSUAwMaAYYS6ZA "Courses")  -  [fig file](https://intranet.hbtn.io/rltoken/1JL-gCkfJ5Hqb0Sf2lmymw "fig file")

And “Duplicate to your Drafts” to have access to all design details.

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4f394f4e4d81250aa214c4e044baf0151c2a81ae051155d59ebfe01f79939b05)

Important notes with Figma:

-   if your computer doesn’t have missing fonts, you can find them here:  [source-sans-pro](https://intranet.hbtn.io/rltoken/4uQkoVbAjr7lRVqSVCWBcw "source-sans-pro")  and  [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/5HnXzrMbtVKLCScrdy4CIg "Spin-Cycle-OT")
-   some values are in float - feel free to round them
-   “Be pixel perfect” - yes! but mainly make sure colors, size and position are correct.  #C271FF  is not  purple.

For this task, please write an amazing  `README.md`

**Interactions note:**

-   Web pages must switch to the tablet version when the screen width is 768px
-   Web pages must switch to the mobile version when the screen width is 576px
-   button hover/active:  `opacity: 0.9`

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `README.md`

Done?  Help  QA Review

### 1. Header first

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Let’s start by the Homepage:  **create the header/hero piece**

Here an archive of all assets needed (for the entire project):

-   [images_images.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/e62e701b6ce0374555e9.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=913aa360ad6fab9b58368b70ef1e038528fbe55901dfc57188557b68a20b3998 "images_images.zip")
-   [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=2440d7c030c1fc46d78bbd57888a2e49ef35de38aaaa189d21a57a927fe95705 "holberton_school-icon.zip")

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/13572c3773e26651761e8b4a74b3383300ed9563.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2c292a063193cc20da22eb033ab46af518db3bef1509b50ba8967b4e4bec1db6)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8854d68a957ef7dc2315.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a8b51c834d54b98acbb3dd1321b0b15e03c7f354a3409a461f1532b0f621352f)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `0-homepage.html, styles.css`

Done?  Help  QA Review

### 2. Carousel of quotes

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the section “Carousel of quotes”**

By using a Carousel component of Bootstrap, create this Carousel of quotes.

You can have for the moment one quote or twice the same for testing (like example below)

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8455560f9ac188658195.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fcd429f9407dbc90f4b7f2ec76f7c090b6c3edbe927c365a981840f2757ef1c4)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `1-homepage.html, styles.css`

Done?  Help  QA Review

### 3. Popular videos

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the section “Most popular tutorials”**

By using a Carousel component of Bootstrap, create this Carousel of video cards.

**Reminder:**

-   Desktop: 4 cards
-   Tablet: 2 cards
-   Mobile: 1 card

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4b610dc2d2cc17ceb2f7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d95e149dfcb191bfd639b54304078ad6a5c124aeed574aa5de402c55ba83bf3a)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `2-homepage.html, styles.css`

Done?  Help  QA Review

### 4. Row of smiles

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the section “Free membership”**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/970efd54768b693bbfac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=51918ce27227efcf56196277749d225af7edfa0171608523d38492afa9cca8af)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `3-homepage.html, styles.css`

Done?  Help  QA Review

### 5. Latest videos

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the section “Latest videos”**

Copy the block “Most popular tutorials” to “Latest videos”

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `4-homepage.html, styles.css`

Done?  Help  QA Review

### 6. ... and the footer!

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the footer**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/739d7cc60098e7ff8f25.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=63c01f7c3026565cdc60f6703fe559327a4a8ca9043967e7807acb5c71a42857)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `homepage.html, styles.css`

Done?  Help  QA Review

### 7. Pricing - header

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Now, let’s do the pricing page:  **create the header/hero piece**

The mobile version must be the same as the Homepage - it’s time to reuse code!

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/ccd30a4d80a990b96740.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9333b55c3afbb319947aedd74f98a42505c8eb587f66c90e6bcc6aba1d3e8f8a)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `0-pricing.html, styles.css`

Done?  Help  QA Review

### 8. Prices grid

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the prices grid**

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/0ac3872946a0014e4f99.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8b4421406dfa0799e6dd10d18e041ff18b8ceb98f9d689f1ecf0f9ab0933e298)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/edea8172b9cc0a867237.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5cb1235e0d696efa9bd5723be0a8c37e433829116614d6c0107d8af67e184462)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `1-pricing.html, styles.css`

Done?  Help  QA Review

### 9. Quotes section

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Same as the Homepage,  **create the Carousel of quotes**

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `2-pricing.html, styles.css`

Done?  Help  QA Review

### 10. FAQ

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the FAQ grid**

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/db8f90e37593a29c1ab6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000037Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=28ca4a0ee31af906a13d4a4077cbed6313866e0f409276031458e37f05f94325)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/eaeb117d40690a451c7b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000037Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2b5856e809b73b205f94e19c1ab28b0946bab03852e399caf61bce9810283524)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `3-pricing.html, styles.css`

Done?  Help  QA Review

### 11. Close the page with a footer

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Same as Homepage,  **create the footer**

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `pricing.html, styles.css`

Done?  Help  QA Review

### 12. Courses - header

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Now, let’s do the courses page:  **create the header/hero piece**

The mobile version must be the same as the Homepage - it’s time to reuse code!

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/a5ba265af5dd643ad942.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000037Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ec43639a79fb53c1ba14f267114f3526db6332aec7878b0c5544874b5da9730b)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `0-courses.html, styles.css`

Done?  Help  QA Review

### 13. Search filters

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the search filters section**

Dropdown is a nice way to create filters.

For the selected/placeholder value of both dropdown, no need to have dynamic value - static content is totally ok.

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/98c0564e59ec5620990e.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000037Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1428c572a49b1c31454b659fadfb99cf55d64dc65d01b0c374071d023e859051)

**Tablet/Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3627550eccca7958d390.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000037Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d9728d908fecb166416aac36c006b72b3886e562960d699a7e97d4ee2490aa6f)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `1-courses.html, styles.css`

Done?  Help  QA Review

### 14. List of result

mandatory

Score:  0.00%  (Checks completed: 0.00%)

**Create the result section of courses**

You can reuse the same cell for testing. Don’t forget to test with odd and even number of cells.

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/76b2074f3f6bbd25cdb9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220130%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220130T000037Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2ecccea08c44f7186d4b95620ba190c87a236a037a8c5f66cd55d3ef15aaf3b5)

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `2-courses.html, styles.css`

Done?  Help  QA Review

### 15. Close the page with a footer

mandatory

Score:  0.00%  (Checks completed: 0.00%)

Same as Homepage and Pricing page,  **create the footer**

**Repo:**

-   GitHub repository:  `holberton-smiling-school`
-   File:  `courses.html, styles.css`

Done?  Help  QA Review

Ready for a manual  second review

Copyright © 2022 Holberton Inc, All rights reserved.