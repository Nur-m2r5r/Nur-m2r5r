# 🔐 Nur  | Security Researcher

<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00FF00&width=435&lines=BIOS%2FUEFI+Specialist;Low-Level+Reverse+Engineer;Security+Tool+Developer" alt="Typing Animation">
</h3>

---

## 🛡️ Core Expertise
<p align="center">
  <img src="https://img.shields.io/badge/Assembly-000000?style=for-the-badge&logo=asm&logoColor=white">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/UEFI-0078D7?style=for-the-badge&logo=intel&logoColor=white">
  <img src="https://img.shields.io/badge/Reverse_Engineering-FF6C37?style=for-the-badge&logo=radar&logoColor=white">
</p>

---

## 🔭 Current Projects

### [BIOS Password Toolkit](https://github.com/Nur-m2r5r/bios-toolkit)
```c
// Sample from bios_analyzer.c
void dump_spi_flash() {
    mmio_write(SPI_CTRL, READ_CMD);
    while(!(mmio_read(SPI_STATUS) & READY_FLAG);
    // Educational purposes only!
}
