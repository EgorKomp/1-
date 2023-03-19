# 1-
Маленькая программа 
class Androidphone(object):
  def init (self, name, Android_version, internet, GB_memory, shelf, camera):
    self.name = name
    self.Android_version = Android_version
    self.internet = internet
    self.GB_memory = GB_memory
    self.shelf = shelf
    self.camera = camera
  def outputphone(self):
    print(self.name)
    print(self.Android_version)
    print(self.internet)
    print(self.GB_memory)
    print(self.shelf)
    print(self.camera)
Android = Androidphone("realme 8","Android 12(now) and UI 3.0(now too)", "4G", 128, "It will be on Android 13 UI4.0", "64mp.")
Android1 = Androidphone("samsung Galaxy A73", "Android 13(now)", "5G", 256, "No, but Samsung Free", "108mp")
#Android2 = Androidphone("")
Android.outputphone()
Android1.outputphone()
