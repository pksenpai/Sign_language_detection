# Sign Language Detection
 - Speak to your computer with your custom sign language!
 - Using Random Forest ML algorithm & mediapipe library.


<img src="test_model2.gif" width="600" height="550">

---------------------------------------------------------------------------
## how to use?
0. install requierments from requirements.txt file:
   
   ```console
   pip install -r requirements.txt
   ```
2. Run `create_dataset.py`, then, by pressing the cue key, put one of your hands in front of the webcam & move your desired sign in different directions and distances.

3. Run `convert_dataset_to_pickle.py` to convert the images of your dataset into a single binary file.(You can use this file more easily than the big dataset of images in other times & systems.

4. Run `train.py` to train your model with pickle dataset & Random Forest algorithm.

5. Finally, run `model.py` to enjoy it! :3

> [!TIP]
> In the following dictionary in ‍‍`model.py`, you can specify a name for each class:
> ```py
> labels_dict = {0: 'Win', 1: 'Luck', 2: 'Perfect'}
> ```
   
