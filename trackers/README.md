Each call of the update function should return a list of detection's with the associated frame detection id and bounding box 
class Detector():
    def __init__(self):
        self.detections = [] # [(frame, id, box)]
        pass
    def getAllDetections(self):
        pass
    def getLandmarkVessel(self):
        pass
    def update(self, frame):
        pass