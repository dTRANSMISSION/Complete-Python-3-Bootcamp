# Complete-Python-3-Bootcamp
Course Files for Complete Python 3 Bootcamp Course on Udemy


Get it now for 95% off with the link:
https://www.udemy.com/complete-python-bootcamp/?couponCode=COMPLETE_GITHUB

Thanks!

To Build: 
```
docker build -t dtran/anaconda3 .
```
To Run: 
```
docker run -t -p 8888:8888 -v $(pwd):/opt/notebooks/Complete-Python-3-Bootcamp dtran/anaconda3  /bin/bash -c "/opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root"
```
