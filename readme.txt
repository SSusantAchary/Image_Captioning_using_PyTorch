***What worked:

Available:
=========
1.  Below is the source code package for Image Captioning.
        https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning
    pkl files for decoder, encoder, vocabulary.
        https://www.dropbox.com/s/ne0ixz5d58ccbbz/pretrained_model.zip?dl=0
        https://www.dropbox.com/s/26adb7y9m98uisa/vocap.zip?dl=0

2. Used this particular because it had MIT License.

Built:
======
1.  Application code(app.py) for interaction of Algorithm and UI(/templates/index.html).
2.  Setup the VM instance, open the ports for application for interaction over HTTP request.

didn't attempt:
==============
1. Training the algorithms needed quite a large amount of data (minimum coco dataset ~14-15 GBs data).
2. Hardware was expensive on cloud to train(no personal GPU based laptops).

***What didn't work:

1. Tried to implement Application to recognize action from video stream(had no prior idea how to use to AWS kinesis video streaming kind of service).
2. OpenPose from CMU had no complete setup steps.