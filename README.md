## 📜 김진호 | 네트워크 엔지니어 포트폴리오

> 안녕하세요! **안정적이고 확장 가능한 인프라 구축**을 목표로 하는 신입 네트워크 엔지니어 김진호입니다.
> 6개월간의 집중적인 학습과 프로젝트 경험을 통해 전통적인 온프레미스 네트워크부터 클라우드, 가상화 환경까지 아우르는 폭넓은 기술 역량을 쌓았습니다. 여러 프로젝트에서 **팀장**을 맡아 기술적 문제 해결은 물론, 팀원들과의 협업을 이끌며 성공적인 결과물을 만들어냈습니다.

<br />

---

### 🛠️ 기술 스택 (Skills)

| 구분 | 기술 |
| :--- | :--- |
| **Networking** | TCP/IP, Routing (OSPF, EIGRP, RIP), Switching (VLAN, STP), Security (Firewall/ASA, ACL, Network Policy), WAN (Frame Relay), NAT, VRRP, DNS (BIND) |
| **Cloud & Virtualization** | AWS (VPC, Subnet, Route Table, IGW/NGW, Security Group, ALB, EC2, Route 53), VMware vSphere (ESXi, vCenter, vSwitch, HA, FT) |
| **Infrastructure as Code** | Terraform |
| **Container & Orchestration**| Kubernetes (Pod, Service, Ingress, Network Policy, ETCD), Docker |
| **Server & OS** | Linux (Rocky), Windows Server, Firewalld, iSCSI, LVM |
| **Server Services** | Web (Apache), FTP (VSFTPD), File Server (NFS, Samba), DB (MariaDB), Mail (Sendmail) |

---

## 🚀 프로젝트 (Projects)

네트워크 엔지니어로서의 역량을 증명하는 핵심 프로젝트들입니다. 각 프로젝트의 상세 내용은 PDF 파일을 통해 확인하실 수 있습니다.

### 1. 🌐 Cisco 라우팅 & 스위칭 기반 네트워크 설계 및 구축
> - **프로젝트 개요**: OSPF, EIGRP 등 다양한 라우팅 프로토콜과 VLAN, STP 등 스위칭 기술을 활용하여 복잡하고 효율적인 기업 네트워크 토폴로지를 설계하고 구축했습니다.
> - **주요 역할 및 사용 기술**:
>   - **Routing**: OSPF, EIGRP, RIP 프로토콜 설정 및 경로 재분배를 통한 최적의 경로 제어
>   - **Switching**: VLAN, VTP, STP(MSTP)를 이용한 L2 네트워크 구성 및 루프 방지
>   - **WAN**: Frame Relay를 이용한 지점 간 광역 네트워크 연결 및 구성
>   - **High Availability**: VRRP를 이용한 게이트웨이 이중화로 서비스 연속성 확보
> - [프로젝트 상세 자료 (PDF)](./path/to/Network_Project.pdf)

### 2. 🛡️ Cisco ASA 방화벽을 활용한 네트워크 보안 구축
> - **프로젝트 개요**: Cisco ASA 방화벽을 중심으로 ACL, NAT, Security Contexts 등 다양한 보안 기능을 적용하여 외부 위협으로부터 내부 네트워크를 보호하는 보안 인프라를 구축했습니다.
> - **주요 역할 및 사용 기술**:
>   - **Firewall Policy**: Cisco ASA 방화벽을 이용한 Inside/Outside/DMZ 보안 정책 설계 및 구현
>   - **Access Control**: ACL(Access Control List)을 활용하여 IP 및 프로토콜 기반의 정밀한 트래픽 제어
>   - **Network Address Translation**: PAT 및 Static NAT를 구성하여 내부 IP 주소 보호 및 외부 서비스 제공
>   - **Virtual Firewall**: 가상 방화벽(Security Contexts)을 구현하여 논리적 네트워크 분리 및 독립적인 보안 정책 적용
> - [프로젝트 상세 자료 (PDF)](./path/to/Firewall_Project.pdf)

### 3. 📦 Kubernetes 클러스터 네트워크 및 보안 관리
> - **프로젝트 개요**: Kubernetes 클러스터의 네트워킹과 보안을 중점적으로 다룬 프로젝트입니다. Pod 간 통신 제어, 외부 서비스 노출 등 컨테이너 환경의 네트워크 운영 역량을 확보했습니다.
> - **주요 역할 및 사용 기술**:
>   - **Network Policy**: Pod 간 Ingress/Egress 트래픽을 제어하여 마이크로서비스 환경의 보안 강화
>   - **Service & Ingress**: ClusterIP, NodePort, Ingress Controller를 활용하여 서비스를 노출하고 트래픽 라우팅
>   - **ETCD Backup/Restore**: 클러스터의 핵심 상태(네트워크 구성 포함)를 백업하고 복구하는 재해 복구 절차 수행
> - [프로젝트 상세 자료 (PDF)](./path/to/Kubernetes_Project.pdf)

### 4. 🖥️ vSphere를 활용한 가상화 네트워크 환경 구축
> - **프로젝트 개요**: VMware vSphere를 활용하여 데이터센터의 물리적 서버 및 네트워크 리소스를 가상화하고, 고가용성(HA) 및 무중단 운영(FT) 환경을 구현했습니다.
> - **주요 역할 및 사용 기술**:
>   - **Virtual Networking**: vSwitch 및 Distributed Switch를 이용한 가상 네트워크 환경 설계 및 VLAN Trunking
>   - **Storage Networking**: iSCSI를 구성하여 가상화 환경의 공유 스토리지 네트워크 구축
>   - **High Availability**: vMotion, HA, FT 기능을 활성화하여 서비스 중단 없는 인프라 구현
> - [프로젝트 상세 자료 (PDF)](./path/to/vSphere_Project.pdf)

### 5. ☁️ AWS 기반 클라우드 네트워크 아키텍처 설계
> - **프로젝트 개요**: 가용성, 확장성, 보안을 고려하여 AWS의 핵심 네트워크 서비스를 이용한 클라우드 인프라를 설계하고 구축한 프로젝트입니다.
> - **주요 역할 및 사용 기술**:
>   - **Network Design**: VPC, Public/Private Subnet, Route Table을 이용한 안전하고 효율적인 네트워크 설계
>   - **Traffic Control**: Security Group, Internet Gateway, NAT Gateway를 이용한 인/아웃바운드 트래픽 제어
>   - **Load Balancing**: Auto Scaling Group과 Application Load Balancer를 연동한 고가용성 아키텍처 구축
> - [프로젝트 상세 자료 (PDF)](./path/to/AWS_Project.pdf)

### 6. 📜 Terraform을 활용한 네트워크 인프라 자동화 (Network as Code)
> - **프로젝트 개요**: Terraform을 사용하여 코드로 AWS 네트워크 인프라를 정의하고, GitHub와 연동하여 자동 배포 환경을 구축하여 수동 작업의 오류를 줄이고 배포 속도를 향상시켰습니다.
> - **주요 역할 및 사용 기술**:
>   - **IaC**: Terraform을 활용한 VPC, Subnet, Security Group, Route Table 등 핵심 네트워크 자원 자동화
>   - **CI/CD**: GitHub Repository 연동을 통한 네트워크 구성 코드의 버전 관리 및 협업
> - [프로젝트 상세 자료 (PDF)](./path/to/Terraform_Project.pdf)

### 7. 🐧 Linux 기반 핵심 네트워크 서비스 구축
> - **프로젝트 개요**: Rocky Linux 환경에서 DNS, DHCP, 방화벽 등 네트워크 운영에 필수적인 핵심 서버 서비스를 직접 구축하고 운영한 프로젝트입니다.
> - **주요 역할 및 사용 기술**:
>   - **IP/Firewall**: 고정 IP 설정 및 Firewalld를 통한 서버 접근 제어
>   - **Core Services**: DNS(BIND), DHCP 서버 구축을 통한 네트워크 기반 서비스 제공
>   - **File Sharing**: NFS, Samba를 이용한 네트워크 파일 공유 시스템 구축
> - [프로젝트 상세 자료 (PDF)](./path/to/Linux_Server_Project.pdf)

<br />

---

### 📞 연락처 (Contact)

- **이메일**: gomim88@naver.com
- **GitHub**: <a href="https://github.com/kimphysicsman">
  <img src="https://user-images.githubusercontent.com/6872828/185908612-22f4d219-78a7-4de7-bb02-deecaa63bffa.png" height="28px" style="margin-top: 10px" />
  </a>
