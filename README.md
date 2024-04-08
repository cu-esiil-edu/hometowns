# Home Towns
A repository for practicing submitting Pull Requests. Please add information about your home town to a .csv file. We will then make a map of everyone's home towns!

## Step 1: Locate the repository you will add your home town info to.

You're already here! Make sure to navigate to the `Code` tab. You should see a list of files in the repository.

## Step 2: Add your changes to the hometowns.csv file

  1. Click on the `hometowns.csv` file. 
  2. Then, click on the edit button in the upper right.
  3. Add at least one new row to the `hometowns.csv` file for your hometown -- that could be where you live now, somewhere you used to live, or another important location for you. You will add the following information to the file, separated by commas:
    
      * **program** you are participating in. The options include: 
      
         1. EDA Certificate
         2. ESIIL Stars
         3. Short Course
         4. Summit
         5. Hackathon
      
      * **date**: today's date in YYYY-MM-DD format (for example, January 5, 2024 would be 2024-01-05)
      * **type**: the type of entry this is. The options include:
      
        1. Where I live now
        2. Place I've lived
        3. Place I love
      
      * **label**: a few sentences about your place
      * **image_url**: the URL to an image you want to display on the hometowns map
      * **image_credit**: how you want to credit your image
      * **latitude**: the latitude of your place
      * **longitude**: the longitude of your place

The file will look something like this once you add your information:  

```csv
program,date,type,label,image_url,image_credit,latitude,longitude
Short Course,2024-04-07,Where I live now,Home of ESIIL at the University of Colorado,https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Flatirons_Winter_Sunrise_edit_2.jpg/2560px-Flatirons_Winter_Sunrise_edit_2.jpg,Taken by Jesse Varner. Modified by AzaToth. - Self-made photo. Originally uploaded on 2006-04-19 by Molas. Uploaded edit 2007-12-23 by AzaToth. CC BY-SA 2.5 https://commons.wikimedia.org/w/index.php?curid=3267545,40.016870,-105.279620
```

## Step 4:  Submit a Pull Request

Commit your changes **in a new branch**:

  1. Click the `Commit` button.
  2. Make sure you are committing **to a new branch**. The name of the branch should look something like `<your-username>-patch-01`, and be towards the bottom of the dialog box.
  3. Write a description of what you did in the description field.
  4. Tag your instructor using `@<instructor-username>`
  4. Click `Commit`.

Now you can make a PR:

  1. Navigate to the `Pull Requests` tab
  2. Click `New Pull Request`
  3. Select your branch, `<your-username>-patch-01` as the head and the `main` branch as the base.
  4. Write a description of your pull request
  5. Click `Submit Pull Request`.
