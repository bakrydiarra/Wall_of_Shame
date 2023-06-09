# TESTING

---

## CONTENTS


* [W3C Validator](#w3c-validator)
* [Python Linter](#python-linter)
* [Lighthouse](#lighthouse)


* [MANUAL TESTING](#manual-testing)
 
* [BUGS](#bugs)
  

---


##  W3C Validator

 There was few pages which returned errors, these errors are located within the Django Summernote library and is outwidth my control to edit therefore I have had to include this.

  <details>
<summary>Contact page</summary>
<img src="docs/validation/contact.png">
</details>

<details>
<summary>Create a Persona page</summary>
<img src="docs/validation/create_persona.png">
</details>

<details>
<summary>Delete page</summary>
<img src="docs/validation/delete_page.png">
</details>

<details>
<summary>Index page</summary>
<img src="docs/validation/index.png">
</details>

<details>
<summary>Sign in page</summary>
<img src="docs/validation/log_in.png">
</details>

<details>
<summary>Sign out page</summary>
<img src="docs/validation/log_out.png">
</details>

<details>
<summary>Persona detail page</summary>
<img src="docs/validation/persona_detail.png">
</details>

<details>
<summary>Sign up page</summary>
<img src="docs/validation/sign_up.png">
</details>

<details>
<summary>Search Results page</summary>
<img src="docs/validation/search_results.png">
</details>

---


#### **CSS Validation**

No errors detected.

<details>
<summary>CSS </summary>
<img src="docs/validation/css.png">
</details>

---


## Python Linter

No erros detected.

<details>
<summary>Contact forms.py </summary>
<img src="docs/validation/contact_forms_py.png">
</details>

<details>
<summary>Contact models.py </summary>
<img src="docs/validation/contact_models_py.png">
</details>

<details>
<summary>Contact views.py </summary>
<img src="docs/validation/contact_views_py.png">
</details>

<details>
<summary>Contact admin.py </summary>
<img src="docs/validation/contact_admin_py.png">
</details>

<details>
<summary>Placard views.py </summary>
<img src="docs/validation/placard_views_py.png">
</details>

<details>
<summary>Placard models.py </summary>
<img src="docs/validation/placard_models_py.png">
</details>

<details>
<summary>Placard forms.py </summary>
<img src="docs/validation/placard_forms_py.png">
</details>

<details>
<summary>Placard admin.py </summary>
<img src="docs/validation/placard_admin_py.png">
</details>

---


## Lighthouse

Overall the results are good. The performance criteria shows in some pages the lowest score due to the down-loaded pictures.

<details>
<summary>Contact page</summary>
<img src="docs/validation/contact_desktop.png">
<img src="docs/validation/contact_mobile.png">
</details>

<details>
<summary>Create a Persona page</summary>
<img src="docs/validation/create_desktop.png">
<img src="docs/validation/create_mobile.png">
</details>

<details>
<summary>Detail Persona page</summary>
<img src="docs/validation/detail_desktop.png">
<img src="docs/validation/detail_mobile.png">
</details>

<details>
<summary>Index page/ Persona list</summary>
<img src="docs/validation/index_desktop.png">
<img src="docs/validation/index_mobile.png">
</details>

<details>
<summary>Search Results page</summary>
<img src="docs/validation/search_desktop.png">
<img src="docs/validation/search_mobile.png">
</details>

<details>
<summary>Sign up page</summary>
<img src="docs/validation/sign_up_desktop.png">
<img src="docs/validation/sign_up_mobile.png">
</details>

<details>
<summary>Sign in page</summary>
<img src="docs/validation/sign_in_desktop.png">
<img src="docs/validation/sign_in_mobile.png">
</details>

<details>
<summary>Sign out page</summary>
<img src="docs/validation/sign_out_desktop.png">
<img src="docs/validation/sign_out_mobile.png">
</details>

---

## Jshint 

no error to be found.


<details>
<summary>Javascript Code</summary>
<img src="docs/validation/js_validation.png">
</details>


## MANUAL TESTING

### Browser Compatibility

  - Testing has been carried out on the following browsers :
  - Safari on macOS Ventura (Safari  Version 13.0.1)
  - Chrome Version Version  Version 108.0.5359.124 

### Test Cases and Results

 - Chrome Developer tools and Mozilla Firefox Web Developer Tools were used throughout the development of the site to test functionality, responsive 
    behaviour, alignment correctness etc:
     - BakckBerry z30
     - BlackBerry PlayBook
     - iPhone SE
     - iPhone XR
     - iPad Air
     - Surface Duo
     - Nest Hub
     - Nest Hub Max

#### Responsive Design

 - The display of the site has been made responsive to allow it to adapt for instance the grid structure layout to a single column.

<details>
<summary>Demo</summary>
<img src="docs/features/responsive.gif">
</details>

---

## Testing the user experience

### Viewing and Navigation


1. As a site owner I want to be able to restrain the access of the content with a log in required to ensure the privacy of WoS users.


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Mandatory Log in  | User click on the website link  | User not authenticated had to log in or register  | Works as expected |


<details>
<summary>Demo</summary>
<img src="docs/features/mandatory_login.gif">
</details>


---

2. As a site user, I want to be able to see the navigation bar so that I can easily navigate

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Nav Bar  | Click on the Wall of Shame link and scroll to the top of any page  | Nav Bar to be displayed along the top of the page or via a hamburger toggle if on a smaller screen wit active links to navigate the site | Works as expected |


<details>
<summary>Demos</summary>
<img src="docs/features/navbar.gif">
</details>

---

3. As a site user, I want to be able to see the footer, so that I can be redirected to social media relating to the website

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Footer  | Log in and scroll to the bottom of any page  | Footer to be displayed along the bootom of the page | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/footer.gif">
<img src="docs/features/links.gif">
</details>

---

4. As a site user, I want to be able to see a pagination so that I can easily navigate.


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Pagination  | Logged in  and scroll to the bottom of the landing page  | Pagination to be displayed along the bootom of the page if there's more than 6 personas published per page | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/pagination.gif">
</details>

---

5. As a site user, I want to be able to see likes so that I can view the number of likes on each persona
6. As a site user, I want to be able to see comments so that I can view the number of comments on each persona

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Likes  | whilst logged in the landing page offered a list of personas each cards show number of likes. If one card clicked the number of likes is still visible  | User logged see successfully a list of persona with number of likes and when one persona clicked this information is still available | Works as expected |


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Comments  | whilst logged in the landing page offered a list of personas each cards show number of comments. If one persona clicked the number of comments is still visible and resumed twice  | User logged see successfully a list of persona with number of comments and when one clicked this information is still available, even twice | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/like_comment.gif">
</details>

---

### Registration and User Accounts


7. As a site user I want to be able to create an account with a user name and password so that I can log in to access content.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Register  | Navigate to Wall of shame site and click on the Sign up button located below the log in section or click of the logo WoS or Register btn in navbar. Fill in the form with the required fields for registration and click on the sign up button.  | User created an account with the information provided in the form  | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/register.gif">
</details>


---

8. As a site user, I want to be able to login or logout so that I can acces or quit the content of the site


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Log in  | Navigate to the Wall of shame site and from the log in page enter your username and password then click on the log in button  | User to log in and be redirected to the landing page | Works as expected |


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Log out  | From any page whilst logged in click on the sign out button located in the right of the nav bar, or if using a small screen device from the list from the hamburger menu toggle.  | Logged in user logged out successfully and is redirected to the log in page | Works as expected |

<details>
<summary>Demos</summary>
<img src="docs/features/logout.gif">
<img src="docs/features/login.gif">
</details>

---

### Persona

9. As a site user, I want to be able to see a list of persona, so that I can select one and discover more about the one selected.
10. As a site user, I want to be able to open a persona, so that I can click on a persona so that I can read the full persona.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Read Persona  | log in and the landing page offered a list of personas each. If one is clicked, details are revealed  | User logged see successfully a list of persona  and when one clicked the information are detailed | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/persona.gif">
</details>

---

11. As a site user, I want to be able to create a persona, so that I can share mine with other users.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- |  -------------  | -------------    | ------------- |
|  Create Persona  | log in and scroll the landing page to the click "create a persona" button. | User clicked sucessfully on the "create a persona" button and is redirected to a form to fill out. Once the form is successfully filled out, the user is redirected on the landing page and its persona will be place in last position. Odered by the date of creation  | Works as expected |


<details>
<summary>Demo</summary>
<img src="docs/features/create_persona.gif">
</details>

---

12. As a site user, I want to be able to update my persona, so that I can show other perspectives/ correct mistakes or improve content


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Update Persona  | Log in and navigate to the persona detail by clicking on the persona in question. At the bottom of the persona card click on the edit button, the edit post form will show redirect to an uptdate form. | User clicked sucessfully on the "edit" button at the bottom of one of his own persona and  is redirected to a form to fill out. Once the form is successfully filled out, the user is redirected on the landing page and its persona will be place in last position. Odered by the date of creation/update  | Works as expected |


<details>
<summary>Demo</summary>
<img src="docs/features/edit_persona.gif">
</details>

---

13. As a site user, I want to be able to delete my persona, so that I can control my content in the app


| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Delete Persona  | Log in and navigate to the persona detail by clicking on the persona in question. At the bottom of the persona card click on the delete button. | User clicked sucessfully on the "delete" button at the bottom of one of his own persona and  is redirected to a page where his demand is to be confirmed. Once the confirmation is successfully validated, the user is redirected on the landing page and its persona deleted persona is nowhere to be found.  | Works as expected |


<details>
<summary>Demo</summary>
<img src="docs/features/delete_persona.gif">
</details>

---

### Contact

14. As a site user, I want to be able to contact the sie owner, so that I can report a matter.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Contact Form  | From any page click on the contact button located in the right of the nav bar, or if using a small screen device from the list from the hamburger menu toggle.  | User clicked on the button and  successfully redirected to a contact form. Once the form is successfully filled out, the user is redirected on the landing page  | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/contact.gif">
</details>

---

### Comment

15. As a site user, I want to be able to comment personas so that I can interact with the other persona owners.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Post Comment  | From any persona detail page whilst logged in fill in the comment form below the persona and press "post comment" button . | Logged in user filled the comment form and clicked button. Once the form submitted, the user can see its comment odered from the oldest to the newest and the count of comments changed | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/post_comment.gif">
</details>

---

### Like/unlike

16. As a site user, I want to be able to like/unlike persone, so that I can show my appreciation of another user's persona.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Like/Unlike  | From any persons detail page whilst logged in go under the persona and clik like or unlike button.  | Logged in user filled clicked the button under the persona. Once the button has been clicked, the count of likes changed and the button itself as well | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/like_unlike.gif">
</details>

---

### Feedback

17. AS a site user, I want to be able to receive feedback when I interact with the site so that I can know if my actions are successfully.

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Message succes/error  | Register. Log in. Log out. Fill a form.  | when the user used a features a success or error message appeared on the top of the page | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/messages.gif">
</details>

---

### Search

18. As a site user, I want to able to search for with some keywords so that I can find a Persona with certain information

| Feature       | Action        | Expected Result  | Actual Result |
| ------------- | ------------- | -------------    | ------------- |
|  Search  | From any page whilst logged in write on the serach field and click the search button located in the right of the nav bar, or if using a small screen device from the list from the hamburger menu toggle  | when the user wrote a keyword and pressed the search button, he is redirected to the results page | Works as expected |

<details>
<summary>Demo</summary>
<img src="docs/features/search.gif">
</details>

## BUGS

During the project I encountered a number of bugs, most of them resulted from mispelling mistakes, case sensitiveness or carless erros during coding.

| Bug           | Fix           |
| ------------- | ------------- |
| Django urls not working | While I was working on the contact app. I couldn't render the template for contact due to the unecessary url home that I copied and pasted from the app placard. Once I deleted the url. The url for contact worked |
| Django urls not working | As I wrote the url for PersonaSearch, I forgot to erase the parentheses added automatically by IDE. Once the parentheses were gone. The url worked |
| Class View PersonaDetail not working | It was impossible to render the detail of persona due to misspelling and lower/uppercase sensitiveness. Once the word liked was propoerly corrected. The PersonaDetail could work |
| Class View PersonaLike  not working| It was impossible to render the view of like because the parameter of the Class was starting with a lowercase. Once it was corrected. The class PersonaLike could work |
| An overide function from the Class View PersonaDetail not working   | The attribute "user.username" wasn't existed in the data models. Therefore couldn't be called. The ForeignKey user was enough and was indeed existing in the data model  |
| Allauth Django not working | Due to a missing comma, an error kept comming in the terminal. Once the comma was added. It worked properly|


<details>
<summary>Coding Erros</summary>
<img src="docs/errors/mispelling_1.png">
<img src="docs/errors/mispelling_2.png">
<img src="docs/errors/comma_problem.png">
<img src="docs/errors/lowercase_problem.png">
<img src="docs/errors/url_home_problem.png">
<img src="docs/errors/url_search_problem.png">
<img src="docs/errors/attribute_problem.png">

</details

---


[Back to README.md](README.md)