# Astron Group Website — Changes Document
**Prepared for:** Wasif (Developer Review & Client Presentation)
**Date:** 2026-06-02
**Client:** Irfan Saab

---

## PART 1 — Changes Already Completed

| # | Section | Before | After | Status |
|---|---------|--------|-------|--------|
| 1 | Chemicals page — intro image | `Network-Security.jpg` (IT-themed, irrelevant) | `Banner-Chemicals-New.jpg` (relevant) | ✅ Done |
| 2 | Luxury Living page — intro image | `Customer-Focus.jpg` (generic stock) | `Banner-Luxury-New.jpg` (relevant) | ✅ Done |
| 3 | IT Distribution page — intro image | `IT-Infrastructure-Banner.jpg` (same as IT Solutions) | `Laptops.webp` (relevant) | ✅ Done |
| 4 | Flex Manufacturing page — intro image | `IT-Infrastructure-Banner.jpg` (wrong) | `Banner-Manufacturing.jpg` (relevant) | ✅ Done |
| 5 | Navbar — hover alignment | Text shifting / misaligned on hover | `inline-flex + align-items:center` — fixed | ✅ Done |
| 6 | Live server — CSS not updating | `functions.php` uploaded to wrong path (`httpdocs/`) | Correct path (`httpdocs/wp-content/themes/astrontech/`) + version bumped | ✅ Done |

---

## PART 2 — Pending Changes (Requested by Irfan Saab)

### HOME PAGE

| # | Item | Before (Current State) | After (Requested) | Status |
|---|------|----------------------|-------------------|--------|
| 1 | Logo slogan | "Group of Companies" in navbar | To be updated — new slogan text needed from client | ⏳ Pending |
| 2 | Hero slider — banner count | 6 slides (includes Digital Marketing) | 5 slides — remove Digital Marketing slide | ⏳ Pending |
| 3 | Hero banner — red heading color | `#C00000` — hard to read on dark banner images | Lighter red tone for better visibility | ⏳ Pending |
| 4 | Hero stat — City Offices | Shows **3** | Change to **5** | ⏳ Waiting on Nameera |
| 5 | IT Distribution BU name | "Astrontech Inc." | **IKonnect Technologies** | ⏳ Pending |
| 6 | Astrontech Pvt Ltd name | Astrontech Pvt. Ltd. | No change — ok as is | ✅ No Change |
| 7 | Astrontech Shenzhen | Not currently on site | **ATECH SHANGHAI POLYMERS (PRIVATE) LIMITED** — websites: atech-shanghai.net / atechshanghai.com (final URL TBD) | ⏳ Waiting on client |
| 8 | Client/customer chip boxes — color | Current dark/neutral background | Brand **red tone** (`#C00000`) | ⏳ Pending |
| 9 | "Our Alliances" section | Present on Home Page | **Remove from Home Page** (will remain on individual BU pages) | ⏳ Pending |
| 10 | "Global Presence" map section | Present on Home Page | **Remove entirely** | ⏳ Pending |
| 11 | "Our Presence" offices section | Present — 3 cities shown | Keep section — update city count per Nameera's confirmation | ⏳ Waiting on Nameera |
| 12 | Ticker scrolling bar | Includes "Digital Marketing Agency" | Remove Digital Marketing item | ⏳ Pending |
| 13 | Navbar dropdown — "What We Offer" | Includes "Digital Marketing" link | **Remove Digital Marketing** from dropdown | ⏳ Pending |
| 14 | Footer | Includes Digital Marketing | **Remove Digital Marketing** from footer | ⏳ Pending |
| 15 | Business Units count stat | Shows **6** Business Units | Update to **5** after Digital Marketing removal | ⏳ Pending |

---

### IT SOLUTIONS PAGE

| # | Item | Before (Current State) | After (Requested) | Status |
|---|------|----------------------|-------------------|--------|
| 1 | Top inner banner | Present | Already exists — ok | ✅ No Change |
| 2 | "Who We Are" — support stat | "24/7 SLA Support" | **"24/7 Support"** | ⏳ Pending |
| 3 | Sub-text under "Pakistan's Leading IT Company" | "Government · Banks · Universities · Enterprises" | **"Catering needs of all verticals"** | ⏳ Pending |
| 4 | Service boxes — interaction | Static cards (image + text) | **Flip on hover** — front shows title/image, back shows brands & detail | ⏳ Pending |
| 5 | IT Infrastructure box — brands | Dell EMC, Lenovo, Huawei, VMware, Veeam | **Dell, Fortinet, VMWare, Veeam, NexaVM, Huawei, Microsoft, RedHat, Attom** | ⏳ Pending |
| 6 | "Networking & Cabling" box — name | Networking & Cabling | **IP Networking & Cybersecurity** | ⏳ Pending |
| 7 | "Networking & Cabling" box — brands | Cisco, Huawei, TP-Link, Sangfor | **Fortinet, Huawei, Omada-TPLink, MonetX, Trendmicro, Kaspersky, HackBox** | ⏳ Pending |
| 8 | Cybersecurity box | Separate box — Fortinet, Sangfor, Trendmicro, Kaspersky | **Remove** — merged into IP Networking & Cybersecurity box | ⏳ Pending |
| 9 | "Surveillance & CCTV" box — name | Surveillance & CCTV | **Surveillance & Video Analytics** | ⏳ Pending |
| 10 | "Surveillance & CCTV" box — brands | Dahua, TP-Link, Atech, VisionLab | **Dahua, VIGI-TPLink, VisionLab** | ⏳ Pending |
| 11 | "End User Computing" box — name | End User Computing | **End User Computing & Printing** | ⏳ Pending |
| 12 | "End User Computing" box — content | Includes RFID, Barcode readers, Zebra | Remove RFID/Barcode. Brands: **Dell, Acer, Dahua, HP, Pantum** | ⏳ Pending |
| 13 | "End User Computing" box — image | Current image | Change to relevant image (content from company profile) | ⏳ Pending |
| 14 | "Software & Licenses" box — image | ERP-themed image | **Replace** — company is not into ERP | ⏳ Pending |
| 15 | "Software & Licenses" box — brands | Microsoft, VMware, RedHat, ERP | **Microsoft, VMWare, Fortinet, Veeam, RedHat, Kaspersky, Trendmicro, NexaVM** | ⏳ Pending |
| 16 | "Email & Collaboration" box | Does not exist | **New box** — Brands: IceWarp, Microsoft. Content: *(as provided by Irfan Saab in Hi Wasif.md)* | ⏳ Pending |
| 17 | "AI Adaptive Learning" box — name | AI Adaptive Learning | **Online & Adaptive Learning** | ⏳ Pending |
| 18 | "AI Adaptive Learning" box — brand | No specific brand shown | **Constructor** | ⏳ Pending |
| 19 | "AI Adaptive Learning" box — image | Business-App.webp (generic) | Replace with suitable image | ⏳ Pending |
| 20 | "Managed Services & SLA" box — position | Currently mid-list | **Move to last position** | ⏳ Pending |
| 21 | "Managed Services & SLA" box — content | Current generic content | Update from company profile | ⏳ Pending — profile document needed |
| 22 | Our Alliances section — display | Text-only brand names | Replace with **actual brand logo images** | ⏳ Pending — logo files needed |
| 23 | Major Customer scrolling boxes — style | Current styling | **Dark grey background, white reverse text** | ⏳ Pending |

---

## PART 3 — Awaiting Client Input (Blockers)

| Item | What Is Needed | From Whom |
|------|---------------|-----------|
| City count update | Exact number of cities and names — currently shows 3 | Nameera |
| Atech Shanghai Polymers | Clarify: does this replace an existing BU or is it a new addition? Which URL to use? | Irfan Saab |
| Banner images | Client asked to review images *before* posting — approval required | Irfan Saab |
| Brand logo files | PNG/SVG logos for Our Alliances section on IT Solutions page | Irfan Saab / Company Profile |
| Company profile document | Referenced multiple times for IT Solutions content (Managed Services, End User Computing, Software) | Irfan Saab |
| IT Distribution page (IKonnect) | Irfan Saab mentioned separate notes coming for this page — awaiting | Irfan Saab |
| Logo slogan change | New slogan text to replace "Group of Companies" | Irfan Saab |

---

## Summary

| Category | Count |
|----------|-------|
| Already completed | **6** |
| Pending — can start now | **27** |
| Blocked — waiting on client input | **7** |
| **Total changes** | **40** |

---

*Note: IT Distribution page (IKonnect) changes have not yet been received. Irfan Saab mentioned these will be shared separately.*
