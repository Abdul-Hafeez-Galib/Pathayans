![Github](https://user-images.githubusercontent.com/64391274/211215734-bbc57b92-9a71-496d-873e-3eedc7523916.png)

# Tour-Inspirer
This is a web-app which will give you suggestions for planning your tour to a destination. We just need to enter our destination and the details of our departure and the return details from that destination, the AI integrated web-app (using OpenAI) will generate the recommended tour plan suggesting the places, food and other things to try out at that place. It basically inspires you to plan your tour and gives you a custom recommended schedule from your departure to the arrival at your original location. It also displays AI generated pics of your destination.

## Team members
1. [Ashish Anton Abraham](https://github.com/Ashish-Abraham)
2. [Abdul Hafeez Galib](https://github.com/Abdul-Hafeez-Galib)
3. [Mohammed Shahadan](https://github.com/Shahadan2001)

## Team Id
krk46H9J0fICmrY6YZZE

## Deployed Link
https://abdul-hafeez-galib-pathayans-main-otedrq.streamlit.app/

NOTE:

(☹️ The Open AI API pricing is changed, so the app shows some error now. Kindly see the product demo video)

## Link to product walkthrough
[Tour-Inspirer Demo-Video](https://www.loom.com/share/cdd2df4ab3f14a468585e2ce32e81b5b)

## How it Works ?
1. Enter the details of your tour - like Destination name, Departure and Arrival Details which includes the date, time and the medium of travel (train, flight, bus etc).
2. Scroll down and the slide the number of images of the destination generated by AI which you want to see.
3. Click the Submit button and wait for the web-app to generate the tour-plan. (using GPT-3 model of Open AI API)
4. Read the tour plan. If you want to listen to the plan as audio, click the audio button.
5. Enjoy the images of your destination generated by AI. (using DALL-E model of Open AI API)

## Libraries used
- Streamlit = v1.13.0 (for building the web-app and deployment)
- openai = v0.26.0 (for generating the tour plan and images using AI)
- gTTS = v2.3.0 (Text to Speech Conversion of the generated tour plan)

## How to configure
1. Clone the Github repo using the git clone command .
2. Make sure you have Python installed in your computer and an IDE.
3. Install the dependencies locally.
    ```
      pip install streamlit
    ```
    
    ```
      pip install openai
    ```
    
    ```
      pip install gTTS
    ```
 4. Create a secrets.toml file inside the .streamlit directory in the project.
 5. Go to Open AI website and login to generate an API Key. Paste it as value of variable openai_api_key in secrets.toml file.
 6. Now the project is ready to be run locally.

## How to Run
Go to the directory of the project and run the following command.
   ```
      streamlit run main.py
   ```

The web-app will open in your default browser and just enter the details as mentioned in the working of the project above and you are all set to plan your tour. 
