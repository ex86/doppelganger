# doppelganger - Hijacking Windows Dll's with mock directories
We can use this exploit to trick any Windows application into loading our DLL by replacing the legitimate DLL via mock directories. Traditionally, DLL hijacking would be achieved when discovering a vulnerable Windows application. With doppelganger, any and all Windows applications are vulnerable.
# Mock Directories
We can archive our Mock Directory via PowerShell =>

![ps](https://user-images.githubusercontent.com/90875279/133706862-3bd7577e-ccdb-44fe-b5c6-e70b2e2c2281.PNG)

Do you notice the trailing space between Windows and System32?
