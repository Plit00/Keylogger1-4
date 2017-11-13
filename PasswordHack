import urllib
import urllb2

url = ""   #target url

values = {'log':'python':'pwd':'python1'}    # u write log&pwd #
headers = {'User-Agent': 'Mozilla/4.0(compatible;MISE 5.5; Windows NT)'}   #website User-Agent#
data = urllib.ulencode(values)

request = urllb2.Request(url.data.headers)
response = urllb2.urlopen(request)

print "#URL:%s" % response.geturl()
print "#CODE:%s" % response.getcode()
print "#INFO:%s" %response.info()
print "#DATA:%s" %response.read()
