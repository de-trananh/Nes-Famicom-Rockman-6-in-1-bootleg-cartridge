# Nes-Famicom-Rockman-6in1-bootleg-cartridge
Easy way to DIY Nes/famicom Rockman 6in1 bootleg cart

# PCB Preparation:
1) Take 3 PCBs to PCB factory (ex: JLCPCB/PCBway,...):
   + CART_RM6i1.zip (this is main cart)
   + PRG_ADAPTOR.zip (this is TSOP48 NOR flash to 32 pins Mask ROM adaptor)
   + VRAM_ADAPTOR.zip (this is SOP28 to DIP32 for CHR RAM)
2) Follow guideline sheet for components soldering
   + TOP soldering
     <img width="1626" height="899" alt="image" src="https://github.com/user-attachments/assets/1fd6b371-318a-4b66-9a8f-256e56d67cbb" />
   + Bottom soldering
     <img width="1273" height="758" alt="image (1)" src="https://github.com/user-attachments/assets/16904828-672f-4f05-b079-809f20edb561" />
# ROMs flashing

## TOOL
  + Im using T48:
    <img width="637" height="345" alt="image" src="https://github.com/user-attachments/assets/64e4a868-a623-4d71-b054-41062cab68b5" />
  + Aliexpress shops:
    https://vi.aliexpress.com/w/wholesale-t48-programmer-xgecu.html?spm=a2g0o.detail.auto_suggest.2.5c08lv7vlv7vcY

# ROM flashing for CHR (SST39SF040 DIP32)
  + Im using XGecuPro tool (T48 version) for rom flashing
  + File: **CHR_512KBytes_SST39SF040.BIN**
  <img width="1177" height="892" alt="image" src="https://github.com/user-attachments/assets/e96375fa-75fb-46fa-a562-b71690886056" />

# ROM flashing for PRG (AM29F016B TSOP48)
  + Im using XGecuPro tool (T48 version) + TSOP 48 to DIP Adapter
  + File: **PRG_2MBytes_AM29F016B.BIN**
  <img width="1181" height="882" alt="image" src="https://github.com/user-attachments/assets/4bd95368-a581-44ad-b716-4e88365df72e" />

# ALTERA CPLD flashing
  + Im using USB blaster via Jtag + Quatus II SW
  + File: **rockman_6in1.pof**
  <img width="712" height="662" alt="image" src="https://github.com/user-attachments/assets/e0e89f05-e51d-4eb2-9ad0-4fb3d58dc2ff" />
  <img width="754" height="360" alt="image" src="https://github.com/user-attachments/assets/7abfd4b3-aa11-480c-a894-5ddfa2703a1d" />

# Enjoy result:
 <img width="1894" height="1240" alt="image" src="https://github.com/user-attachments/assets/16024b1c-33f9-4de6-bcec-678f9d353f40" />
 <img width="612" height="631" alt="image" src="https://github.com/user-attachments/assets/d690b4c3-6b0c-480e-a347-5170be9e592a" />
 <img width="613" height="634" alt="image" src="https://github.com/user-attachments/assets/b82bc604-0ccd-4b2d-859a-f3b3c592fbce" />
 <img width="615" height="639" alt="image" src="https://github.com/user-attachments/assets/9132d6bc-2b76-429d-a8f9-96cdc0eaf572" />
 <img width="617" height="633" alt="image" src="https://github.com/user-attachments/assets/6dbe2a4b-b391-4527-8bdd-3717a1441092" />
 <img width="617" height="637" alt="image" src="https://github.com/user-attachments/assets/58f73d09-456f-438e-a894-b9ace68b8f49" />
 <img width="616" height="637" alt="image" src="https://github.com/user-attachments/assets/39ba7050-ad1c-4127-98d0-515a088b9046" />
 <img width="618" height="630" alt="image" src="https://github.com/user-attachments/assets/4180970c-6ca5-4832-8255-a70eba449c85" />







