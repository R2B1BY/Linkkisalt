# Linkkisalt
import pyshorteners

def kisalt(url):

        shortener = pyshorteners.Shortener()

        short_url = shortener.tinyurl.short(url)

        return short_url

url =input("link gir dostum:")

kisalt = kisalt(url)

print(kisalt)
