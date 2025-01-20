# Exercise 5: Using `textContent`

### Task: How to fork a repository on GitHub.com

1. Click on the **Fork** icon at the top right corner of the repository page on GitHub.com.

2. On the next screen, click the green **Create fork** button to create your own copy of the original repository.

3. Once the fork is created, click the green **Code** button and select **Open with GitHub Desktop**.

4. In GitHub Desktop, clone the repository by choosing a **Local Path** where you want to store a copy on your computer. When prompted about how you plan to use this fork, select **For my own purposes**.

## JavaScript Task:

1. Link to the external JavaScript file placed in the `js` folder:
   ```html
   <script src="js/script.js"></script>
   ```
2. Ensure "use strict" is at the top of your script.js file.

3. Create a `<p>` tag in your HTML with:
   An id attribute set to `text`.
   The text "old content" written between the `<p>` opening and closing tags
      ```html
      <p id="text">old content</p>
      ```

4. Use `document.getElementById` inside your script.js to select the `<p>` tag by its `id` attribute.

5. Use `textContent` to update the text of the <p> tag to:

   ```html
   "This text has been updated with JavaScript!"
   ```

6. Open **Go Live** in your VS Code editor and check that the content has been updated.
