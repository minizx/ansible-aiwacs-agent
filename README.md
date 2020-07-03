aiwacs-agent
=========

시스원 aiwacs nms 에이전트 설치용 ansible 플레이북


Requirements
------------
AiWACS 에이전트 파일 준비 필요 ( 저장경로 : files/ )


Role Variables
--------------
aiwacs 토큰값 (기본값 : 0000000000000000)
aiwacs 서버 IP
aiwacs 서버 포트
aiwacs 에이전트 설치 경로


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: all
  roles:
    - role: ansible-aiwacs-agent
      # 필요 시 변수값 설정
      aiwcas_install_mode: install
      aiwacs_token: 0000000000000000
      aiwacs_server_ip: 1.1.1.1
      aiwacs_server_port: 8891
      aiwacs_dir: /usr/local/aiwacs
      aiwacs_win_dir: c:\aiwacs

```   

License
-------



Author Information
------------------

https://www.sysone.co.kr/product_view.php?idx=28
