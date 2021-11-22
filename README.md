
## Dependency (development environment)

- OS: Ubuntu 14.04
- Python: 2.7
- pip: numpy(1.9), scipy, pandas, sklearn, sklearn-pandas, chainer


## Local testing

validation-set: last 4 weeks.

    $ python make_data.py --validation
    $ python train.py --validation

## Run

    $ ./run.sh
    $ ls -la submission_mlp.csv

