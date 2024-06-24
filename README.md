# How to Run the Application
- Clone the repository
- Run the command "composer install" (no additional packeges are installed.)
- Run the command "php artisan serve"
- The proeject will run on the default URL "http://127.0.0.1:8000/"
  <img src="https://awesomescreenshot.s3.amazonaws.com/image/2580139/48981417-828e569936bf4252fcebe52eeda3267e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJSCJQ2NM3XLFPVKA%2F20240624%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240624T104904Z&X-Amz-Expires=28800&X-Amz-SignedHeaders=host&X-Amz-Signature=eacfc75d5f5439b46b6925dd25ea0a7798c43ffcddc3705b7c96838a0cef79ff" />

# Information about the task
- Provided the Interface to give the inputs for the **Item prices** and selection of **Rule**
- Added the ProductController to perform the form post actions.
- On submit the form will call the action goes to **submit_prices** on the **ProductController**
- Added switch cases for input rule selection from the Form.
- After processing the API will return the same form view with the results.
- At the time of showing results added the script to hide the input form.
