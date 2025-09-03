# Setting up NFS Share across multiple nodes, enable data access from a centralized point simultaneuosly # 
# Data share on NFS are visible across all the docker  nodes #
# The pre-requisite is that we must have more than one node and docker swarm mush be initialized acress all the nodes #
# See the steps below #

<img width="775" height="338" alt="NFS_Share_on_Docker_01" src="https://github.com/user-attachments/assets/429cdf62-0056-4ec3-94c9-725be697f0ac" />
<img width="565" height="275" alt="NFS_Share_on_Docker_02" src="https://github.com/user-attachments/assets/054856be-9d61-49d7-a870-0bb2b601537c" />
<img width="557" height="280" alt="NFS_Share_on_Docker_03" src="https://github.com/user-attachments/assets/1634a964-208b-4615-b01d-006027264f79" />
<img width="557" height="317" alt="NFS_Share_on_Docker_04" src="https://github.com/user-attachments/assets/c4c0513f-ace7-4e1a-81f0-34ae3828f363" />
<img width="779" height="413" alt="NFS_Share_on_Docker_05" src="https://github.com/user-attachments/assets/40358201-cb2d-4714-aa9b-56b5d6c0e47a" />
<img width="478" height="202" alt="NFS_Share_on_Docker_06" src="https://github.com/user-attachments/assets/02c4f29a-5c03-4f45-ba8e-a458d4cad2b9" />
<img width="510" height="197" alt="NFS_Share_on_Docker_07" src="https://github.com/user-attachments/assets/1935a562-0349-4ce4-9b23-7dc73c3b1eef" />
<img width="634" height="262" alt="NFS_Share_on_Docker_08" src="https://github.com/user-attachments/assets/1dbbad90-0fa2-42e0-ae32-44bb6eb99416" />
<img width="675" height="378" alt="NFS_Share_on_Docker_09" src="https://github.com/user-attachments/assets/1ac97c71-2527-4b9f-8ff9-61d7046d2012" />
<img width="656" height="377" alt="NFS_Share_on_Docker_10" src="https://github.com/user-attachments/assets/cac43d43-c082-4aa5-ac4b-f61c00a595fa" />
<img width="783" height="224" alt="NFS_Share_on_Docker_11" src="https://github.com/user-attachments/assets/310afc95-34eb-4977-9922-a84cf2ad65a2" />
<img width="782" height="157" alt="NFS_Share_on_Docker_12" src="https://github.com/user-attachments/assets/8683d632-374c-4e92-81b0-929aeec5657d" />
<img width="779" height="157" alt="NFS_Share_on_Docker_13" src="https://github.com/user-attachments/assets/5530aed1-10e2-47e8-ba43-8f99947428f2" />
<img width="772" height="277" alt="NFS_Share_on_Docker_14" src="https://github.com/user-attachments/assets/fc571e97-35bd-4b4e-8827-caeec32844c2" />
<img width="926" height="281" alt="NFS_Share_on_Docker_15" src="https://github.com/user-attachments/assets/82d02514-4e1c-44c1-8d34-6fa469ca5f0d" />
<img width="811" height="226" alt="NFS_Share_on_Docker_16" src="https://github.com/user-attachments/assets/12c6e5f5-4c3a-4640-9bad-1f2af8b3eb7e" />
<img width="791" height="197" alt="NFS_Share_on_Docker_17" src="https://github.com/user-attachments/assets/22262d1d-b523-4d4f-954d-70510122579a" />
<img width="881" height="352" alt="NFS_Share_on_Docker_18" src="https://github.com/user-attachments/assets/2715bd23-b82a-4a80-b52e-164877e1c7a5" />
<img width="759" height="292" alt="NFS_Share_on_Docker_19" src="https://github.com/user-attachments/assets/9cb1d00c-75e0-436b-b2f5-42cfb88b079d" />
<img width="813" height="404" alt="NFS_Share_on_Docker_20" src="https://github.com/user-attachments/assets/b6b37178-aa0f-478f-befa-ece5197421dc" />
<img width="919" height="137" alt="NFS_Share_on_Docker_21" src="https://github.com/user-attachments/assets/bddf4f26-ac96-45d9-9c71-137034dc827b" />
<img width="920" height="208" alt="NFS_Share_on_Docker_22" src="https://github.com/user-attachments/assets/cfd3a1b8-bc02-48de-8595-cf7678e5b8bc" />
<img width="924" height="248" alt="NFS_Share_on_Docker_23" src="https://github.com/user-attachments/assets/a68635bd-d896-4516-8895-c6cb1974af5c" />
<img width="908" height="344" alt="NFS_Share_on_Docker_24" src="https://github.com/user-attachments/assets/76ac2e0b-1c6c-4829-911d-d28431a36114" />
<img width="904" height="251" alt="NFS_Share_on_Docker_25" src="https://github.com/user-attachments/assets/f4e4d769-45c0-40e5-8f74-475d23b16f39" />
<img width="913" height="269" alt="NFS_Share_on_Docker_26" src="https://github.com/user-attachments/assets/fceb81a4-1d5a-488e-ae86-da1562174caf" />
<img width="724" height="160" alt="NFS_Share_on_Docker_27" src="https://github.com/user-attachments/assets/36df51a3-8e85-408a-a30f-9f6bc2652a37" />
<img width="783" height="158" alt="NFS_Share_on_Docker_28" src="https://github.com/user-attachments/assets/9c30c1bb-10da-43d7-ae57-9471bc594553" />
<img width="797" height="160" alt="NFS_Share_on_Docker_29" src="https://github.com/user-attachments/assets/793bce09-b48b-4edc-a19a-d3da00adaa8b" />
