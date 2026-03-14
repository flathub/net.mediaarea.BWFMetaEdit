# BWF MetaEdit

___Embed, validate, and export BWF files metadata___

This tool permits embedding, editing, and exporting of metadata in Broadcast WAVE Format (BWF) files. 
This tool can also enforce metadata guidelines developed by the Federal Agencies Audio-Visual Working Group, 
as well as recommendations and specifications from the European Broadcasting Union (EBU), Microsoft, and IBM.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub net.mediaarea.BWFMetaEdit
flatpak run net.mediaarea.BWFMetaEdit
```

## Building

```bash
git clone git@github.com:flathub/net.mediaarea.BWFMetaEdit.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install net.mediaarea.BWFMetaEdit.json
```
