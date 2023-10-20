
## Federated Learning (FL) 

### Pre-requisites
- Ensure you have all necessary packages and dependencies installed as per the provided requirements file.
- Familiarize yourself with the model architecture; any changes should be consistent between the server and clients.

### Instructions

1. **Server Setup**:
   - Open the server script.
   - Set the desired number of clients. The default is set to 3.
   - Specify the number of global iterations as per your requirements. The default is set to 10.
   - Ensure a `.ckpt` file, compatible with the current model architecture, is present in the server directory. You can generate this file using the CKPT Generator script.

2. **Client Setup**:
   - Depending on the number of clients specified in the server script, launch the respective number of client scripts. For instance, if you've set 3 clients, execute 3 separate client scripts.

3. **Training**:
   - Once the minimum number of clients have connected, the training process will commence automatically.

4. **Model Architecture**:
   - If you wish to change the model architecture, ensure it's consistent across both the server and client scripts. As mentioned, a corresponding `.ckpt` file should be generated and made available in the server directory before starting the server.
---