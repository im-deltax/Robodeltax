# Robodeltax

An educational AI chatbot robot under development by [im-deltax](https://github.com/im-deltax).

This repository currently publishes robot design assets: editable 3D files, printable parts, electronics designs, and garment patterns. The main chatbot application and production firmware are not available yet. Learning assistance is the intended application, not a capability demonstrated by this release.

## Current assets

| Folder | Contents |
| --- | --- |
| `Blender/` | Current assembled Kimono scene, V21 |
| `Vo_In_3D/` | Printable STL parts and available editable CAD/STEP sources |
| `Trang_Phuc/` | Current V20 garment patterns, sewing documents, print artwork and textures |
| `Dien_Tu/` | KiCad sources, custom libraries, prototype manufacturing exports and assembly documents |
| `Nguon_CAD_Giu_Lai/` | Older CAD retained for reference; not the current printing set |
| Other outfit folders | Design variants and reference-based studies, including folders marked `BANSAO` (copies); these are not all current approved manufacturing sets |

Read **[MO_FILE_NAY_TRUOC.txt](MO_FILE_NAY_TRUOC.txt)** first for the current version selection and assembly limitations. `rule.md` contains design notes for the current robot, not general dimensions for every design variant.

## Development and validation status

- Main AI chatbot software and robot firmware: under development, not included.
- Complete PCB, battery, servo and cable fit inside the enclosure: not confirmed.
- Electronics: prototype designs, not electrically validated on physical hardware.
- V21 updates the 1.9-inch display mounting; the proposed head rotation and 4.5 mm neck lift are not integrated.
- Native CAD coverage is partial: the current V21 FreeCAD/STEP set covers the head/display mount, not a complete newly rebuilt body CAD assembly.
- Garment patterns should be printed at 100% scale and their calibration marks checked before cutting.

Do not treat the presence of manufacturing exports as proof of a fully tested or production-ready robot. Follow the wiring and USB-mode notes in the original documents.

## Downloading large files

Large design assets use Git LFS. Install Git LFS, then run:

```sh
git lfs install
git clone https://github.com/im-deltax/Robodeltax.git
cd Robodeltax
git lfs pull
```

## Licensing and provenance

Copyright (C) 2026 Trần Minh Triết (im-deltax).

Unless a file or component states otherwise, original copyrightable material in this repository owned by Trần Minh Triết is licensed under the **GNU General Public License, version 3 only (GPL-3.0-only)**. See [LICENSE](LICENSE) for the complete terms. This includes the original design files and documentation to the extent the author owns the applicable copyright. This notice does not add chatbot software or firmware that has not yet been published.

Third-party components, libraries, artwork and reference-derived material retain their own licenses and rights; this notice does not relicense material the author does not own. Folder names such as `BANSAO` alone do not establish authorship or licensing. Provenance of reference-derived material remains to be documented.

GPL-3.0 permits commercial use. Obligations depend on how covered works are modified and conveyed; see the actual license rather than assuming every private modification must be published. Applying GPL to design files is not hardware certification, physical validation or a grant of third-party rights.

## Contributing

Please open an issue for questions, reproducibility reports, documentation corrections or proposed contributions. Include the file/version used and distinguish simulated results from physical tests. Do not post credentials or private user conversations.

---

## Tiếng Việt

Robodeltax là dự án robot chatbot AI hỗ trợ học tập đang phát triển. Bản công khai ban đầu gồm thiết kế vỏ, điện tử, cảnh Blender và rập trang phục; **chưa có source chatbot chính hoặc firmware hoàn chỉnh**. Đọc `MO_FILE_NAY_TRUOC.txt` để chọn đúng bộ hiện hành. Chưa xác nhận lắp vừa toàn bộ linh kiện hoặc kiểm thử điện thực tế. Phần tài nguyên gốc thuộc quyền sở hữu của Trần Minh Triết được cấp phép GPL-3.0-only, trừ khi có ghi chú khác. Thành phần bên thứ ba giữ giấy phép và quyền tương ứng, nguồn gốc tài nguyên tham khảo cần được ghi rõ.

