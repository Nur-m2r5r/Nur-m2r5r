# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Shield.png" width="28px"> Nur_234m3 | Security Researcher

<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=BIOS%2FUEFI+Security+Specialist;Low-Level+Reverse+Engineer;Firmware+Security+Researcher" alt="Typing Animation">
</h3>

---

## 🔍 Core Competencies

<p align="center">
  <img src="https://img.shields.io/badge/x86_64-000000?style=flat&logo=assemblyscript&logoColor=white">
  <img src="https://img.shields.io/badge/UEFI-0078D7?style=flat&logo=intel&logoColor=white">
  <img src="https://img.shields.io/badge/Reverse_Engineering-FF6C37?style=flat&logo=radar&logoColor=white">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white">
</p>

---

## 🛠️ Active Research Projects

### [BIOS Security Toolkit](https://github.com/Nur_234m3/bios-toolkit)
```c
// SPI Flash Dumper (Educational Use Only)
void dump_firmware(uint8_t* buffer) {
    mmio_write(SPI_CTRL, READ_CMD);
    while(!(mmio_read(SPI_STATUS) & READY_FLAG);
    mmio_read_block(SPI_DATA, buffer, FLASH_SIZE);
}
