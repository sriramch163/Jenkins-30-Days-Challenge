# Jenkins-30-Days-Challenge

A 30-day hands-on challenge repository with one example per day showing Jenkins pipeline examples, small Python apps, Dockerfiles, and CI/test examples. The goal is to provide bite-sized Jenkins/CI-CD learning material you can clone and run locally.

How to use
- Clone the repo and explore the `Day - X/` folders.
- Each day contains a `Jenkinsfile` (pipeline example) and a `README.md` describing that day's exercise.
- Some days include runnable examples (`app.py`, `test_app.py`), Dockerfiles, and `requirements.txt` to demonstrate building and testing within pipelines.

Repository structure (summary)

Top-level folders: Day - 1 through Day - 30. Below is a per-day summary of notable files.

- Day - 1/
	- `Jenkinsfile` — pipeline example
	- `README.md`

- Day - 2/
	- `Jenkinsfile`
	- `README.md`

- Day - 3/
	- `Jenkinsfile`
	- `README.md`

- Day - 4/
	- `Jenkinsfile`
	- `README.md`

- Day - 5/
	- `Jenkinsfile`
	- `README.md`

- Day - 6/
	- `Jenkinsfile`
	- `README.md`

- Day - 7/
	- `Jenkinsfile`
	- `README.md`

- Day - 8/
	- `Jenkinsfile`
	- `README.md`

- Day - 9/
	- `app.py` — small Python example app
	- `Jenkinsfile`
	- `README.md`

- Day - 10/
	- `app.py`
	- `Jenkinsfile`
	- `README.md`
	- `test_app.py` — unit test for the sample app

- Day - 11/
	- `app.py`
	- `Jenkinsfile`
	- `README.md`
	- `requirements.txt` — Python dependencies

- Day - 12/
	- `app.py`
	- `Dockerfile` — containerize example app
	- `Jenkinsfile`
	- `README.md`

- Day - 13/
	- `app.py`
	- `Dockerfile`
	- `Jenkinsfile`
	- `README.md`

- Day - 14/
	- `app.py`
	- `Dockerfile`
	- `Jenkinsfile`
	- `README.md`

- Day - 15/
	- `app.py`
	- `Jenkinsfile`
	- `README.md`

- Day - 16/
	- `Jenkinsfile`
	- `README.md`

- Day - 17/
	- `Jenkinsfile`
	- `README.md`

- Day - 18/
	- `app.py`
	- `Jenkinsfile`
	- `README.md`
	- `test_app.py`

- Day - 19/
	- `Jenkinsfile`
	- `README.md`

- Day - 20/
	- `Jenkinsfile`
	- `README.md`

- Day - 21/
	- `Jenkinsfile`
	- `README.md`

- Day - 22/
	- `Jenkinsfile`
	- `README.md`

- Day - 23/
	- `Jenkinsfile`
	- `README.md`

- Day - 24/
	- `Jenkinsfile`
	- `README.md`

- Day - 25/
	- `Jenkinsfile`
	- `README.md`

- Day - 26/
	- `Jenkinsfile`
	- `README.md`

- Day - 27/
	- `Jenkinsfile`
	- `README.md`
	- `vars/sayHello.groovy` — shared pipeline step / Groovy helper

- Day - 28/
	- `Jenkinsfile`
	- `README.md`

- Day - 29/
	- `Jenkinsfile`
	- `README.md`

- Day - 30/
	- `app.py`
	- `Dockerfile`
	- `Jenkinsfile`
	- `README.md`
	- `requirements.txt`
	- `test_app.py`

Notes and next steps
- To run the Python examples locally: create a virtual environment, install the `requirements.txt` if present, and run `python app.py` or `pytest` where tests exist.
- For Docker examples: build with `docker build -t day-XX .` and run locally to test container behaviour.
- The `Jenkinsfile` in each folder is a starting point — you can point a Jenkins pipeline at any day's folder to experiment with the pipeline shown.

Contributing
- Feel free to open issues or PRs to improve examples, add documentation, or update pipeline patterns.

License
- Check repository root or contributor notes for license information.
