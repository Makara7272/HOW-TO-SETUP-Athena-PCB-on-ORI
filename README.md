# How to Collect Data from Crash Test

## Installation Guide
Follow these steps to set up **Athena PCB** for data collection.

---

## Step 1: Hardware Setup

### Install Athena PCB
- Place the **Athena PCB** inside the correct slot in the box on **ORI**.
- The correct location is inside the **motorcycle's neck, under the front light**.

### Connect the Power Supply
- Ensure the power connection is properly connected to the **motorcycle battery** using a connector.
- **Recommended connector:** [JAE MX23A34SF1](https://www.digikey.hk/en/products/detail/jae-electronics/MX23A34SF1/1969213).

### Extend the USB Cable
- Use an **extended USB wire** to reach the required length for testing.
- Make sure the cable is **long enough** to accommodate movement on the road.

### Connect the USB to TTL Converter
- Attach the **extended USB cable** to the **CH340G USB to TTL Converter**.
- **Recommended converter:** [CH340G USB to TTL](https://electropeak.com/ch340g-usb-ttl?srsltid=AfmBOoqIVB9tZcSFh_Yg7OWTaLfCPxLS8sZD9Pl17J2JHyX1jCWZCQiw).
- Connect the **RX (Receive) pin** from the TTL converter to the **Athena board**.

---

## Step 2: Firmware Setup

### Open Serial Debug Assistant
- Run the **Serial Debug Assistant** program on your computer.
- Check if the **COM port** is detected.

#### If the device is not detected, check:
- The **USB cable connection**.
- The **USB shield** by connecting it directly to the computer.

### Configure the Serial Debug Settings
- Locate the **"Stop Bits"** setting. Change the setting from **"Close"** to **"Open"**.
- You should now see **Acceleration (X, Y, Z) and Roll, Pitch, Yaw** data on the screen.

---

## Troubleshooting
- If **no data appears**, try flipping the **RX (Receive) pin** that connects to the Athena board.

---

## Final Notes
- Make sure all **connections** are secure before testing.
- The **USB cable** should be properly **shielded** to avoid interference.
- Always **double-check** the **port** and **baud rate settings** in the **Serial Debug Assistant**.

