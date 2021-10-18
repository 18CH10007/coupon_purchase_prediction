# Kaggle-Coupon-Purchase-Prediction

Code for [Coupon Purchase Prediction](https://www.kaggle.com/c/coupon-purchase-prediction)


## Dependency (development environment)

- OS: Ubuntu 14.04
- Python: 2.7
- pip: numpy(1.9), scipy, pandas, sklearn, sklearn-pandas, chainer

## Data

Place the [data files](https://www.kaggle.com/c/coupon-purchase-prediction/data) into a subfolder ./data. And unzip. (requires `coupon_list_train.csv`, `coupon_list_test.csv`, `user_list.csv` and `coupon_detail_train.csv`)

## Local testing

validation-set: last 4 weeks.

    $ python make_data.py --validation
    $ python train.py --validation

## Run

    $ ./run.sh
    $ ls -la submission_mlp.csv

