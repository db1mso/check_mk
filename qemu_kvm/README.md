**Beschreibung:**
Mit dem "qemu" CMK-Plugin können virtualle Maschinen in der qemu/KVM Umgebung überwacht werden

**Installation:**
Mit MPK:
check_mk -P install qemu-1.0.mkp

Manuell:
CMK-Host:   den Agent aus "agent/plugins/qemu" nach "/usr/lib/check_mk_agent/local/" kopieren
CMK-Server: den Check aus "checks/qemu" nach "/omd/sites/SITE/local/share/check_mk/checks/" kopieren

**Screenshot:**
![ScreenShot](https://github.com/christianbur/check_mk/blob/master/qemu_kvm/screenshort_qemu.png)

**Performance Data:**
  - cpu_%
  - memory_current_%
  - memory__assigned_MB 
