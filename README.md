# CT-Autoencoder
Training an autoencoder neural network to remove noise from CT images.
Using traditional ASIR processing as a starting point, comparison with GE's DLIR algorithm, my own autoencoder network, and a traditional lowpass filter.
My results are the "Reconstr. ASIR"

Given the results, I would guess that GE maybe filters out part of the image (likely noise) and then only runs DL processing on that part of the image, in order to maintain accuraccy. Their size of model and number of training samples likely also exceeds mine (I only had 2 patient's scans for training, one for testing). 
![image](https://github.com/user-attachments/assets/74fc2abc-9ba0-4ab5-8a64-63e6692bf518)

![image](https://github.com/user-attachments/assets/bc5a3041-d3dd-41bd-bb5c-ca39b930cf4f)
