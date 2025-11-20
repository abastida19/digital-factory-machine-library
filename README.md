# Digital Factory Machine Library

This repository contains a structured machine classification ontology and a comprehensive machine library in JSON format for use in digital factory simulations, production line automation, and layout generation workflows.  
It is designed to work with Python pipelines, Omniverse USD scenes, and AI-driven production line builders.

---

## 📦 Contents

### **machine_library.json**
This file defines a standardized taxonomy of machines commonly used in industrial production lines, including:

- Conveyors  
- Robots (6-axis, SCARA, Delta, Cobot, Cartesian)  
- Forming and gluing equipment  
- Cutting and packaging machines  
- Inspection systems  
- Sorting and reject mechanisms  
- Feeding & buffering systems  
- Manual workstations  
- End-of-line palletizing systems  

Each machine entry includes:
- `internal_id`: stable unique ID for automation scripts  
- `category` and `subtype`: machine family and function  
- `unspsc`: global industry classification code  
- `description`: 3-sentence technical description  
- `tags`: semantic keywords  
- `default_usd_asset`: placeholder path for future USD models  

The library is versioned and can be extended at any time.

---

## 🎯 Purpose

This library enables:

- Automated production-line generation  
- Layout placement in NVIDIA Omniverse USD Composer  
- Machine-type validation  
- Digital twin modeling  
- AI-assisted factory design  
- Consistent classification across different pipelines  

It is intended as a foundation for simulation, visualization, and integration of industrial equipment in virtual factories.

---

## 🛠️ Updating the Library

To update `machine_library.json`, you can either:
- Edit it online through GitHub (recommended for simple changes), or  
- Update it locally and push changes using Git.

Steps:
```bash
git add machine_library.json
git commit -m "Detailed description of change"
git push
