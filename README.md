# Create-Windows-Service
Framework to Create a windows Service


Be sure to add python executable to Enviormental Varibles




To Fix Error:

Error starting service: The service did not respond to the start or control request in a timely fashion.


I know this is old but I was stuck on this forever. For me, this specific problem was solved by copying this file - pywintypes36.dll

From -> Python36\Lib\site-packages\pywin32_system32

To ->  Python36\Lib\site-packages\win32



To install/ update service:

>>Python MyService install

To uninstall service:

>>Python MyService remove
