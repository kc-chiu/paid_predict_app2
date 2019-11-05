# Paid Web App for Plant Disease Prediction 

Final Project (Build a Startup) of [Make Money with Machine Learning course](https://www.machinelearningcourse.io/courses/make-money) by [Siraj Raval](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A)

------------------

## Requirements

- Python 3.6+
- Python Modules listed in [requirements.txt](https://github.com/kc-chiu/paid_predict_app2/blob/master/app/requirements.txt)

------------------

## Trying the app

- All app codes are in [app](https://github.com/kc-chiu/paid_predict_app2/tree/master/app) folder
- Install Python Modules listed in [requirements.txt](https://github.com/kc-chiu/paid_predict_app2/blob/master/app/requirements.txt)
- Download [pre-trained model](https://drive.google.com/file/d/1FZXraDDPqbRTX-QeiQclfojgtoLddxQ_/view) to [app/models](https://github.com/kc-chiu/paid_predict_app2/tree/master/app/models) folder (file size: 123MB)
- Run [app.py](https://github.com/kc-chiu/paid_predict_app2/blob/master/app/app.py)
- Sign up with some test data
- Payment info (test mode)
  - Card no: 4242 4242 4242 4242
  - Expiry date: any date in the future
  - CVC: any 3-digit integer
- Try prediction with leaf images in [samples](https://github.com/kc-chiu/paid_predict_app2/tree/master/samples) folder or other leaf images you have.

------------------

## References
1. [Flaskex for user sign-up and log-in](https://github.com/anfederico/Flaskex)
2. [Stripe payment](https://github.com/bprakashx7/stripe_payments)
3. [Plant Disease Recognition](https://github.com/saroz014/Plant-Diseases-Recognition) for the pre-trained model