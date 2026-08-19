### 1️⃣ Step 1: Plug In (Hold Button)                                                                             
                                                                                                                   
  1. Hold down the white BOOTSEL button on your Pico 2.
  2. Plug it into your laptop USB.
  3. Release the button.
  (A drive named RP2350 will appear on your screen).
  ──────
  ### 2 Step 2: Run Setup (In Terminal)
  
  Open your terminal and run:
  
    unzip Pico2_Ubuntu_GPIO.zip
    cd pico2_gpio
    ./setup.sh
  
  (Takes 5 seconds. It flashes the board and installs all commands).
  ──────
  ### 3 Step 3: Test It
  
    pico-gpio test


#### Step 1: Extract the Zip
  
    unzip Pico_GPIO_Studio.zip
    cd pico2_gpio
  
  #### Step 2: Run the 1-Click Automated Setup
  
    bash setup.sh
  
  This installs the Python driver, creates the desktop icon, and registers USB plug-and-play permissions.          
  
  #### Step 3: Plug in your Pico 2 & Activate
  
    ./activate.sh
