# coordinates
# how to get the your coordinates using python.

pip install geocoder
import geocoder
def get_coordinates():
    return geocoder.ip('me').latlng

coordinates = get_coordinates()
print("your current coordinates are:", coordinates)
