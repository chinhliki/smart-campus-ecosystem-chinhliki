# Minh chứng Buổi 1

Thư mục này dùng để nộp minh chứng thiết lập môi trường lab.

## Sinh viên điền thông tin

- Họ tên: Đinh Ngọc Chính
- Mã sinh viên: 1771020103
- Nhóm: 6B
- Vai trò dự kiến trong nhóm: Backend Developer (phụ trách Core Business Service)
- Hệ điều hành: Windows 10 (PowerShell + Docker Desktop)
- Ghi chú: Đã cài đặt đầy đủ Git, Docker, Docker Compose, Node.js và Python. Docker hoạt động bình thường (đã test với hello-world).

## Các file minh chứng nên có

- `tool-versions.txt`
- `docker-version.txt`
- `compose-version.txt`
- `hello-world.txt`
- `smoke-test-result.txt`
- `image-list.txt`
- `git-log.txt`
- `checklist.md`
- `known-issues.md`

## Cách sinh file tự động

macOS/Linux:

```bash
./scripts/collect_session01_evidence.sh
```

Windows:

```powershell
.\scripts\collect_session01_evidence.ps1
```

