# Minh chứng Buổi 1

Thư mục này dùng để nộp minh chứng thiết lập môi trường lab.

## Sinh viên điền thông tin

- Họ tên: Vũ Đức Nam
- Mã sinh viên: 1771020484
- Nhóm: (điền tên nhóm của bạn tại đây)
- Vai trò dự kiến trong nhóm: Developer
- Hệ điều hành: Windows 11 (WSL2 – Docker Desktop)
- Ghi chú: Môi trường đã được thiết lập hoàn chỉnh. Tất cả Docker image đã pull thành công, smoke test PASS toàn bộ.

## Các file minh chứng

| File | Trạng thái |
|---|---|
| `tool-versions.txt` | ✅ Đã sinh |
| `docker-version.txt` | ✅ Đã sinh |
| `compose-version.txt` | ✅ Đã sinh |
| `hello-world.txt` | ✅ Đã sinh |
| `smoke-test-result.txt` | ✅ Đã sinh |
| `image-list.txt` | ✅ Đã sinh |
| `git-log.txt` | ✅ Đã sinh |
| `checklist.md` | ✅ Đã điền |
| `known-issues.md` | ✅ Đã điền |
| `service-boundary.md` | ✅ Đã điền |
| `pull-images-result.txt` | ✅ Đã sinh |

## Cách sinh file tự động

macOS/Linux:

```bash
./scripts/collect_session01_evidence.sh
```

Windows:

```powershell
.\scripts\collect_session01_evidence.ps1
```

## Thông tin môi trường

- **Git**: 2.47.1
- **Docker**: 29.1.3
- **Docker Compose**: v2.40.3-desktop.1
- **Node.js**: v24.15.0
- **Python**: 3.12.6
- **pip**: 24.2
