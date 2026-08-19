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
