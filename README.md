# 🌟 Welcome To (সহজ সরল সিম্পল) Assignment - 5

# **📅 Deadline For 60 marks:** 9th March, 2026 (11:59 pm ⏱️)  
#  📅 No Deadline For 50 marks  
# **📅 Deadline For 30 marks:** Any time after 9th March.

---

# Assignment-05: GitHub Issues Tracker


### **API Endpoints:**
###  **All Issues:** 
  - https://phi-lab-server.vercel.app/api/v1/lab/issues 


###  **Single Issue:**
   - https://phi-lab-server.vercel.app/api/v1/lab/issue/{id}

   - Example: https://phi-lab-server.vercel.app/api/v1/lab/issue/33


###  **Search Issue:** https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q={searchText}

   - Example:  https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q=notifications


---

## 📝 Main Requirements

## 🎨 Design Part

## Login Page
- Create a login page containing a logo, title, and sub-title
- Below that, there will be 2 inputs, a sign-in button, and a demo credential to sign in. Follow the Figma for this page 
- Styled as per Figma

## Main Page: 

### Navbar: 

- Navbar with website logo/name on the left
- Search input and button on the right

### Tab Section like Figma: 

- 3 tab ( All, Open, Closed) at the top of this section.(**All**, **Open**, **Closed**)

- Below the tab, there will be an icon, the issue count, some text on the left, and an open and closed marker on the right

- Responsiveness: The website should be responsive for mobile devices. It is totally up to you. 


--- 


## ⚙️ Functionalities
- In login page, there will be default admin credentials (username, password). You need to sign in using these credentials.

- Load all issues and display as per Figma

- On clicking on an open or closed tab, it will load the issues data of the related tab and show it in a display-like card in a 4-column layout like Figma. By default, it will show all data 

- Each card shows:
  - Title
  - Description
  - Status 
  - Author
  - Priority
  - Label
  - CreatedAt
- Clicking on an issue  card will open a modal and show all the information about that Issue. 

### 🚀 Challenges


- Show the card Top border based on their category(open, closed), open card will have Green Boder, closed card will have a purple border on top. 

- Loading spinner on data load

- Show active button on changing category names

- Implement Search Functionality and 8 meaningful github commit.  

- Create a readme file and answer this question on your own. Don’t copy-paste from Google or any AI chatbot. 
    1 What is the difference between var, let, and const?

Ans:
var: This is the old way of doing things. It’s a bit "loose" because you can declare the same variable name multiple times, which often leads to annoying bugs in your code.

let: This is the modern and disciplined version. You can change its value later (like updating a score), but you aren't allowed to re-declare it in the same block.

const: Think of this as a person of their word. Once you set a value, it stays that way forever and cannot be changed.

2 What is the spread operator (...)?

Ans:
The spread operator is like a magic tool that unpacks everything from a bag (an array or object) and pours it into a new one. It’s super helpful when you want to copy data or merge multiple lists into one without messing up the original.

3 What is the difference between map(), filter(), and forEach()?

Ans:
map(): This is like a factory machine. You feed it a list, it processes every single item, and hands you back a brand-new list with the results.

filter(): This acts as a strainer. You give it a condition, and it catches only the items that match, giving you a new list with just those specific parts.

forEach(): This is just a worker that goes through the list one by one to do a task (like logging to the console), but it doesn't create or return anything new.

4 What is an arrow function?

Ans:
It’s a sleek, shorthand way of writing functions in modern JavaScript. Instead of typing out the whole word function, you just use a cool "arrow" symbol () => {}, which makes your code look much cleaner and easier to read.

5 What are template literals?

Ans:
These are a lifesaver for writing strings. Instead of using quotes and plus signs to join text and variables, you use backticks (`) and just drop your variables directly inside ${}. It makes handling dynamic text much smoother.

---

## 🛠️ Technology Stack

- **HTML**
- **CSS** (Vanilla/Tailwind/DaisyUI)
- **JavaScript** (Vanilla)

---

## 🔑 Demo Credentials

```text
Username: admin
Password: admin123
```


---

### Optional: 
 - No need to show status: Open, Closed styles On modals. 
 - No Need to show icon on labels 
 - No need to apply styles on Priority 
--- 


## 📤 What to submit

- **GitHub Repository Link:**
- **Live Site Link:**

---


