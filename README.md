# ASU-PCTF
ASU PCTF project. This is a tool to protect us against BOF & format strings vulns. The project consists of two parts: network one and system one. The network part will be in charge of filtering out all traffic that looks similar to BOF/format string exploitation and stealing this exploit if possible. The system part will be libc wrapper that will eliminate BOF & format string vulns. The wrapper should be preloaded with LD_PRELOAD mechanism.