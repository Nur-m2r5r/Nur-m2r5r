# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Shield.png" width="28px"> Nur_234m3 | Security Researcher

<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=4000&pause=1000&color=#b2f233&center=true&vCenter=true&width=500&lines=BIOS%2FUEFI+Security+Specialist;Low-Level+Reverse+Engineer;Firmware+Security+Researcher" alt="Typing Animation">
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
<p align="center"> <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Nur-m2r5r&show_icons=true&theme=dark&hide_border=true&include_all_commits=true&count_private=true&hide_title=true"> <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Nur-m2r5r&theme=dark&hide_border=true"> </p><p align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=Nur-m2r5r&theme=react-dark&hide_border=true&area=true"> </p>
<p align="center"> <a href="mailto:research@nur234m3.io"><img src="https://img.shields.io/badge/Email-Professional%20Inquiries-important?style=flat&logo=protonmail"></a> <a href="https://twitter.com/Nur_234m3"><img src="https://img.shields.io/badge/Twitter-Academic%20Discussions-informational?style=flat&logo=twitter"></a> <a href="https://www.linkedin.com/in/nur234m3"><img src="https://img.shields.io/badge/LinkedIn-Collaborations-blue?style=flat&logo=linkedin"></a> </p>
<div align="center"> <sub>Last updated: {DATE} | PGP: <a href="https://keys.openpgp.org">0xABCDEF1234567890</a></sub> </div>

### [BIOS Security Toolkit](https://github.com/Nur-m2r5r/bios-toolkit)
// SPI Flash Dumper (Educational Use Only)
```
void dump_firmware(uint8_t* buffer) {
    mmio_write(SPI_CTRL, READ_CMD);
    while(!(mmio_read(SPI_STATUS) & READY_FLAG);
    mmio_read_block(SPI_DATA, buffer, FLASH_SIZE);
}
