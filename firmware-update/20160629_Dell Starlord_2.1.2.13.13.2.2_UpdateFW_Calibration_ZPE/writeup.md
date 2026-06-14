# Reverse the binary firmware update of DELL

**index**

- [1.what this firmware update?](#-1what-this-firmware-update)

- 2.What this file is type?

	- 2.1.with file (what this file?)

	- 2.2.with strings (what data can read hardcode in file?)

	- 2.3.with binwalk (what files hidden in the file binary?)

- 3.Debugging with ghidra
	
	- 3.1.Import the file binary into ghidra

	- 3.2.What architecture firmware support and proof?

	- 3.3.why firmware read the binary when firmware is hardware run before operating system, proof?

- 4.Debugging with KVM windows10 and see how to works?

# 1.what this firmware update?