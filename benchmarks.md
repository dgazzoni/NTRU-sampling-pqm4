# Speed Evaluation
## Key Encapsulation Schemes
| scheme | implementation | key generation [cycles] | encapsulation [cycles] | decapsulation [cycles] | sample_fixed_type [cycles] |
| ------ | -------------- | ----------------------- | ---------------------- | ---------------------- | -------------------------- |
| ntruhps2048509 (10 executions) | clean | AVG: 57,355,222 <br /> MIN: 57,355,205 <br /> MAX: 57,355,243 | AVG: 1,060,178 <br /> MIN: 1,060,175 <br /> MAX: 1,060,209 | AVG: 2,372,977 <br /> MIN: 2,372,977 <br /> MAX: 2,372,977 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhps2048509 (10 executions) | m4f | AVG: 2,689,844 <br /> MIN: 2,689,722 <br /> MAX: 2,690,025 | AVG: 390,729 <br /> MIN: 390,591 <br /> MAX: 390,965 | AVG: 538,338 <br /> MIN: 538,338 <br /> MAX: 538,338 | AVG: 156,096 <br /> MIN: 155,822 <br /> MAX: 156,263 |
| ntruhps2048509-shuffling (10 executions) | clean | AVG: 57,328,790 <br /> MIN: 57,328,769 <br /> MAX: 57,328,823 | AVG: 826,903 <br /> MIN: 826,893 <br /> MAX: 826,927 | AVG: 2,372,985 <br /> MIN: 2,372,982 <br /> MAX: 2,373,014 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhps2048509-shuffling (10 executions) | m4f | AVG: 2,535,940 <br /> MIN: 2,535,925 <br /> MAX: 2,535,994 | AVG: 235,187 <br /> MIN: 235,176 <br /> MAX: 235,212 | AVG: 538,488 <br /> MIN: 538,488 <br /> MAX: 538,488 | AVG: 13,313 <br /> MIN: 13,308 <br /> MAX: 13,326 |
| ntruhps2048677 (10 executions) | clean | AVG: 103,405,586 <br /> MIN: 103,405,579 <br /> MAX: 103,405,618 | AVG: 1,844,459 <br /> MIN: 1,844,456 <br /> MAX: 1,844,489 | AVG: 4,358,075 <br /> MIN: 4,358,065 <br /> MAX: 4,358,099 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhps2048677 (10 executions) | m4f | AVG: 4,332,472 <br /> MIN: 4,332,132 <br /> MAX: 4,332,798 | AVG: 552,700 <br /> MIN: 552,350 <br /> MAX: 553,065 | AVG: 807,150 <br /> MIN: 807,150 <br /> MAX: 807,150 | AVG: 226,850 <br /> MIN: 226,563 <br /> MAX: 227,165 |
| ntruhps2048677-shuffling (10 executions) | clean | AVG: 103,390,985 <br /> MIN: 103,390,965 <br /> MAX: 103,391,011 | AVG: 1,501,376 <br /> MIN: 1,501,361 <br /> MAX: 1,501,405 | AVG: 4,358,074 <br /> MIN: 4,358,065 <br /> MAX: 4,358,098 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhps2048677-shuffling (10 executions) | m4f | AVG: 4,111,185 <br /> MIN: 4,111,174 <br /> MAX: 4,111,225 | AVG: 327,138 <br /> MIN: 327,127 <br /> MAX: 327,145 | AVG: 806,658 <br /> MIN: 806,655 <br /> MAX: 806,688 | AVG: 18,352 <br /> MIN: 18,349 <br /> MAX: 18,367 |
| ntruhps4096821 (10 executions) | clean | AVG: 149,851,527 <br /> MIN: 149,851,501 <br /> MAX: 149,851,536 | AVG: 2,447,325 <br /> MIN: 2,447,319 <br /> MAX: 2,447,353 | AVG: 5,874,742 <br /> MIN: 5,874,732 <br /> MAX: 5,874,766 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhps4096821 (10 executions) | m4f | AVG: 5,739,552 <br /> MIN: 5,739,206 <br /> MAX: 5,739,899 | AVG: 681,402 <br /> MIN: 681,028 <br /> MAX: 681,787 | AVG: 1,014,168 <br /> MIN: 1,014,168 <br /> MAX: 1,014,168 | AVG: 286,920 <br /> MIN: 286,542 <br /> MAX: 287,154 |
| ntruhps4096821-shuffling (10 executions) | clean | AVG: 149,412,450 <br /> MIN: 149,412,409 <br /> MAX: 149,412,464 | AVG: 2,013,009 <br /> MIN: 2,012,990 <br /> MAX: 2,013,057 | AVG: 5,874,745 <br /> MIN: 5,874,732 <br /> MAX: 5,874,766 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhps4096821-shuffling (10 executions) | m4f | AVG: 5,449,210 <br /> MIN: 5,449,185 <br /> MAX: 5,449,255 | AVG: 395,702 <br /> MIN: 395,685 <br /> MAX: 395,749 | AVG: 1,014,371 <br /> MIN: 1,014,368 <br /> MAX: 1,014,401 | AVG: 22,260 <br /> MIN: 22,230 <br /> MAX: 22,303 |
| ntruhrss701 (10 executions) | clean | AVG: 106,121,869 <br /> MIN: 106,121,853 <br /> MAX: 106,121,892 | AVG: 1,528,152 <br /> MIN: 1,528,152 <br /> MAX: 1,528,152 | AVG: 4,416,105 <br /> MIN: 4,416,095 <br /> MAX: 4,416,129 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
| ntruhrss701 (10 executions) | m4f | AVG: 4,210,228 <br /> MIN: 4,210,222 <br /> MAX: 4,210,256 | AVG: 370,050 <br /> MIN: 370,050 <br /> MAX: 370,050 | AVG: 863,315 <br /> MIN: 863,315 <br /> MAX: 863,315 | AVG: 0 <br /> MIN: 0 <br /> MAX: 0 |
## Signature Schemes
| scheme | implementation | key generation [cycles] | sign [cycles] | verify [cycles] |
| ------ | -------------- | ----------------------- | ------------- | --------------- |
# Memory Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | Key Generation [bytes] | Encapsulation [bytes] | Decapsulation [bytes] |
| ------ | -------------- | ---------------------- | --------------------- | --------------------- |
| ntruhps2048509 | clean | 25,400 | 20,452 | 18,788 |
| ntruhps2048509 | m4f | 21,360 | 14,068 | 14,792 |
| ntruhps2048509-shuffling | clean | 24,532 | 19,612 | 18,788 |
| ntruhps2048509-shuffling | m4f | 20,528 | 13,228 | 14,792 |
| ntruhps2048677 | clean | 34,312 | 27,784 | 25,532 |
| ntruhps2048677 | m4f | 28,472 | 19,980 | 19,720 |
| ntruhps2048677-shuffling | clean | 33,184 | 26,620 | 25,568 |
| ntruhps2048677-shuffling | m4f | 27,344 | 18,852 | 19,720 |
| ntruhps4096821 | clean | 40,940 | 33,028 | 30,420 |
| ntruhps4096821 | m4f | 35,224 | 23,420 | 24,280 |
| ntruhps4096821-shuffling | clean | 39,580 | 31,668 | 30,420 |
| ntruhps4096821-shuffling | m4f | 33,864 | 22,060 | 24,280 |
| ntruhrss701 | clean | 32,892 | 26,124 | 25,924 |
| ntruhrss701 | m4f | 27,528 | 18,316 | 20,552 |
## Signature Schemes
| Scheme | Implementation | Key Generation [bytes] | Sign [bytes] | Verify [bytes] |
| ------ | -------------- | ---------------------- | ------------ | -------------- |
# Hashing Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | Key Generation [%] | Encapsulation [%] | Decapsulation [%] |
| ------ | -------------- | ------------------ | ----------------- | ----------------- |
## Signature Schemes
| Scheme | Implementation | Key Generation [%] | Sign [%] | Verify [%] |
| ------ | -------------- | ------------------ | -------- | ---------- |
# Size Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | .text [bytes] | .data [bytes] | .bss [bytes] | Total [bytes] |
| ------ | -------------- | ------------- | ------------- | ------------ | ------------- |
| ntruhps2048509 | clean | 10,180 | 0 | 0 | 10,180 |
| ntruhps2048509 | m4f | 191,824 | 0 | 0 | 191,824 |
| ntruhps2048509-shuffling | clean | 9,488 | 0 | 0 | 9,488 |
| ntruhps2048509-shuffling | m4f | 192,280 | 0 | 0 | 192,280 |
| ntruhps2048677 | clean | 10,548 | 0 | 0 | 10,548 |
| ntruhps2048677 | m4f | 281,568 | 0 | 0 | 281,568 |
| ntruhps2048677-shuffling | clean | 9,864 | 0 | 0 | 9,864 |
| ntruhps2048677-shuffling | m4f | 282,364 | 0 | 0 | 282,364 |
| ntruhps4096821 | clean | 10,284 | 0 | 0 | 10,284 |
| ntruhps4096821 | m4f | 370,076 | 0 | 0 | 370,076 |
| ntruhps4096821-shuffling | clean | 9,592 | 0 | 0 | 9,592 |
| ntruhps4096821-shuffling | m4f | 371,152 | 0 | 0 | 371,152 |
| ntruhrss701 | clean | 10,116 | 0 | 0 | 10,116 |
| ntruhrss701 | m4f | 264,492 | 0 | 0 | 264,492 |
## Signature Schemes
| Scheme | Implementation | .text [bytes] | .data [bytes] | .bss [bytes] | Total [bytes] |
| ------ | -------------- | ------------- | ------------- | ------------ | ------------- |
