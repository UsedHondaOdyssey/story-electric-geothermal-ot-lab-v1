# story-electric-geothermal-ot-lab-v1
Run a geothermal power plant in your browser and learn OT/IT security. Walk the plant, operate the HMI, power the town, trace packets, edit live firewall rules, follow Kerberos &amp; MFA, hunt in SOC logs and see NERC CIP mapped to real controls. Or turn off the safeties and blow it all up. Free, open source, built with Claude.

# ⚡ Story Electric · Geothermal OT/IT Security Lab

**Run a power plant. Keep the lights on. Or turn off the safeties and blow it all up, and learn OT security along the way.**

**[![▶ Play the Lab](https://img.shields.io/badge/▶_Play_the_Lab-Live_in_your_browser-00c2ff?style=for-the-badge)](https://usedhondaodyssey.github.io/story-electric-geothermal-ot-lab-v1/)** · free, no install, no login
Works best in a desktop browser (Chrome, Edge, Firefox, Safari); touch controls on phones and tablets.

Story Electric is a fictional geothermal power plant you can walk through, run and break, to learn how
operational technology (OT) and IT work together, and how they're secured. It's not a comprehensive
simulation; it's a hands-on, gamified way to learn the basics.

## 🎮 Play
- ⚡ **Power the neighborhood:** start up the plant, sync to the grid and watch the town's lights come on
- 💥 **Break it:** turn off the safety protections, push the plant past its limits, and watch the turbine,
  generator and transformer go up in flames (then learn which protection would have stopped it)
- ⏱️ **Work a shift:** follow grid demand, spot faults early on the PI trends, and keep the plant online
- 🎯 **Red vs blue:** replay a real-world-style attack against your own firewall rules, then hunt it in the logs
- 🚨 **Incident drill:** an attacker is stopping your cooling fans. Contain it before the turbine trips
- 🕵️ **Easter eggs:** hidden around the plant. Some of them go boom.

## 📚 Learn
- 🏭 **Walk the plant** in first person: control building stacked by Purdue level, turbine hall, wellfield,
  cooling yard, switchyard and a town on the grid
- 🖥️ **Operate the HMI** and watch the plant respond: dispatch, trips, and protection systems
- 📦 **Trace packets** hop by hop, and X-ray real protocol fields (Modbus, DNP3, IEC 61850, Kerberos, TLS…)
- 🧱 **Edit live firewall rules** and see what an attacker could reach from any compromised device
- 🔐 **Follow authentication** across separate IT and OT Active Directory forests, the VPN, MFA and the jump host
- 🔍 **Hunt in SOC logs** with an XQL-style query console
- 🗂️ **Run OT security operations:** asset inventory, vulnerability triage, patching, change management,
  and USB media control
- 📜 **See NERC CIP mapped to the lab,** with a live audit-readiness score

Built with [Claude](https://claude.ai). Feel free to fork it, modify it to your heart's content, or reach out with ideas!

---

## ⚠️ Disclaimer

**Educational use only.** This project is a learning tool. It is not a real control system, product,
training certification, or authoritative reference.

- **Fictional.** Story Electric, its people, accounts, IP addresses, network design and data are invented.
  Any resemblance to a real organization or system is coincidental. Real-world incidents are referenced
  only as publicly reported history.
- **Simplified.** Plant physics, protocols, timings and security controls are simplified for teaching and
  may not match any specific vendor, product or site. Don't use it to design, operate or assess a real system.
- **Not compliance, legal or engineering advice.** NERC CIP, IEC 62443 and other standards are summarized
  in plain language and may be incomplete or out of date. Applicability and requirements depend on your
  organization; always consult the current official standards and your compliance, legal and engineering teams.
- **Defensive focus.** Attack scenarios show *why* controls exist and how defenders detect and respond.
  The lab contains no working exploit code and performs no real network activity. Only test systems you
  own or are explicitly authorized to test.
- **Cartoon destruction.** Explosions and the hidden easter eggs are game effects, included to show why
  physical security and safety systems matter.
- **No data collected.** The lab runs entirely in your browser. Progress is saved only in your own
  browser's local storage. Nothing is sent to a server.
- **Provided as-is,** without warranty of any kind. See the [License](#-license).

Not affiliated with, endorsed by, or representing NERC, ISA/IEC, any utility, or any vendor or company.

---

## 💬 Feedback
Found a bug or an inaccuracy, or have an idea? [Open an issue](../../issues). Corrections from OT and grid
practitioners are especially welcome.

## 📄 License
Released under the [MIT License](LICENSE). Free to use, copy, modify and share, including commercially,
as long as the copyright notice is kept. © 2026 YOUR NAME

3D rendering by [three.js](https://threejs.org) (MIT License).
