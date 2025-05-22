# tcp seq-ack 정리

* SYN, FIN flag 설정이 들어가면 Sequence number 1 증가한다.
* Sequence Number(RAW), Acknowledge(RAW) 는 랜덤 값이 들어간다.
* Ack flag 설정은 Acknowlege(RAW) 가 유의미한 값을 가질경우 세팅된다. (초기 3-way hand shaking SYN 첫 패킷 외에 모든 패킷에 세팅된다.)
* Retransmission 발생했을 경우, Sequence Number는 증가하지 않는다.

<p align="center">
<image src="https://github.com/YangBeomu/s_develop_tcp-seq-ack/issues/1#issue-3081757616"></p>
