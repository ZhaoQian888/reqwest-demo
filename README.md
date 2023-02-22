

# 测试记录

## 第一次试验(100ms 请求一次,请求100次，进行json解析)
ave cost = 781.537µs
ave cost = 829.58µs
ave cost = 784.846µs
ave cost = 785.858µs
ave cost = 794.385µs
794.6us


## 第二次试验(连续请求100次，进行json解析)
ave cost = 380.812µs
ave cost = 381.272µs
ave cost = 380.736µs
ave cost = 396.675µs
ave cost = 372.345µs

381us

## 第三次试验(连续请求100次，不进行json解析)
ave cost = 355.697µs
ave cost = 344.609µs
ave cost = 362.105µs
ave cost = 348.143µs
ave cost = 358.26µs

353us