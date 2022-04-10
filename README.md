# WASM examples

### wasmLoad.html
webassembly 코드를 실행 예제.  
byteArray변수에 데이터는 [wat2wasm demo](https://webassembly.github.io/wabt/demo/wat2wasm/)의 example: simple의 wasm 파일의 데이터를 element 당 1바이트 씩 표현한 것.  
wasm 파일을 다운로드 받은 후 ```xxd -g1 test.wasm``` 명령어로 다운로드 받은 wasm 파일의 데이터를 확인할 수 있음.


### addTwoPerformance.html
단순히 두 수를 더하는 계산을 js와 wasm으로 실행했을 때 실행 시간 비교.

### fibonacci.html
피보나치 수열 계산을 js와 wasm으로 실행했을 때 실행 시간 비교.

