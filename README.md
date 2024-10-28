# macos
## Changing binding on a keyboard
```
hidutil property --set '{"UserKeyMapping":[{"HIDKeyboardModifierMappingSrc":0x7000000E2,"HIDKeyboardModifierMappingDst":0x7000000E3},{"HIDKeyboardModifierMappingSrc":0x7000000E3,"HIDKeyboardModifierMappingDst":0x7000000E2},{"HIDKeyboardModifierMappingSrc":0x700000035,"HIDKeyboardModifierMappingDst":0x700000064},{"HIDKeyboardModifierMappingSrc":0x700000064,"HIDKeyboardModifierMappingDst":0x7000000E2}]}'
```


Reference :https://developer.apple.com/library/archive/technotes/tn2450/_index.html

![image](https://github.com/user-attachments/assets/b115a07f-a4cd-448c-a739-f2e04383f3d1)
