---
title: TrueNAS + Veeam como solución de Backups centralizada
summary: Esquema de respaldos sobre TrueNAS (ZFS) y Veeam con políticas de retención, pruebas de restauración y reportes.
tags: [Backups, TrueNAS, Veeam, Disaster Recovery]
date: 2024-03-20
lastmod: 2025-11-11
image:
  filename: featured.png   # captura de TrueNAS o Veeam (jobs, repos)
  focal_point: Center
---

Implementé una solución de **backup centralizada**:

- **Repositorio** en **TrueNAS** con ZFS, scrubs y verificación de integridad.
- **Veeam** para VMs y servidores físicos, jobs por criticidad y ventanas de backup.
- **Políticas de retención** y alertas automáticas.
- **Pruebas de restauración** periódicas (file-level y full VM) para auditoría.

**Resultado:** menor RTO/RPO y trazabilidad completa de respaldos.

