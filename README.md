project name: Final project

test the application: python -m unittest test_emotion_detection
run the package: 
`
from EmotionDetection import emotion_detector
result = emotion_detector("I hate working long hours.")
print(result)
`
run the server:
`
python3 server.py
`

build the package:
`
python3 -m pip install build
python3 -m build
python3 -m pip install --force-reinstall dist/*.whl
`

code analysis:
`
python3 -m pip install pylint
pylint server.py
`