# Onnx Runtime
Wrapper for the Microsoft Onnx Runtime [onnx runtime](https://onnxruntime.ai/docs/install/#inference-install-table-for-all-languages)

# Description
Perform inference or training using onnx models. 
CPU onnx libs are included for macOS and Linux. 

# Linux
## CUDA
CUDA tries to link by default. As outlined via the addon_config.mk file. 
Will fallback to CPU if not present. 

# macOS
## Copy dylibs in Xcode 
If there is an error regarding the onnx runtime dylib not linking.
Copy to the executables in the Build Phases tab.
<img width="1060" height="630" alt="image" src="https://github.com/user-attachments/assets/61cb70d5-a4af-4a3d-83c0-daf10527566f" />

