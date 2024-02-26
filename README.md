**README**

**Webcam Live Streaming with Flask**

This Python script allows you to stream live video from your laptop's webcam to any device connected to the same network, such as your mobile phone or tablet. It utilizes the Flask web framework to create a simple web server and OpenCV library to capture video from the webcam.

**Requirements:**
- Python 3.x
- OpenCV library (`opencv-python`)
- Flask web framework (`flask`)

**Installation:**
1. Ensure you have Python installed on your system. If not, download and install it from [python.org](https://www.python.org/downloads/).
2. Install the required libraries by running the following command in your terminal or command prompt:
   ```
   pip install opencv-python flask
   ```

**Usage:**
1. Clone or download the repository containing the script.
2. Open a terminal or command prompt and navigate to the directory containing the script (`security_camera.py`).
3. Run the script using the following command:
   ```
   python main.py
   ```
4. Once the script is running, it will start streaming live video from your laptop's webcam.
5. On your mobile device or any other device connected to the same network, open a web browser.
6. Enter the IP address of your laptop followed by port 5000 (e.g., `http://<your_laptop_ip>:5000`) in the address bar.
7. You should see the live video stream from your laptop's webcam displayed in the web browser.

**Notes:**
- Ensure your laptop and the device accessing the stream are connected to the same network.
- Replace `0.0.0.0` with your laptop's IP address if needed.
- Make sure to properly close the camera when stopping or interrupting the script.

**Security Considerations:**
- By default, the streaming server is accessible to anyone on the same network. If you want to restrict access, consider implementing authentication mechanisms or configuring network settings accordingly.

**Author:** [Musa Tahawar]

**License:** This project is licensed under the [MIT License], see the LICENSE file for details.

For any issues or inquiries, please feel free to contact [Musa Tahawar/musahero1999@gmail.com/musatahawar.epizy.com]. 

**Acknowledgements:**
Special thanks to the Flask and OpenCV development communities for providing excellent tools and resources.
