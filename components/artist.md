# Component: Artist

Hiển thị trang chi tiết nghệ sĩ và các đề xuất liên quan.

## 🧩 Props

| Tên prop          | Kiểu dữ liệu    | Mô tả |
|-------------------|-----------------|-------|
| `infoArtist`      | `object`        | Thông tin nghệ sĩ chính |
| `listArtistRelated` | `object`      | Danh sách nghệ sĩ liên quan |
| `listDataAllPage` | `object`        | Danh sách dữ liệu từng trang |
| `titlePage`       | `string`        | Tiêu đề trang |
| `onScrollDown`    | `function`      | Callback khi scroll |
| `changeOrder`     | `function`      | Hàm đổi thứ tự hiển thị |
| `seoData`         | `object`        | Dữ liệu SEO |
| `currentSortId`   | `string`        | ID sắp xếp hiện tại |

## 🧠 Mô tả chức năng

- Hiển thị avatar, thông tin cá nhân nghệ sĩ
- Hiển thị các nghệ sĩ liên quan
- Giao diện phân trang và load thêm khi scroll

## 📎 Liên kết

- Sử dụng: `@components/basic/Card`
- Dữ liệu từ: `@helpers/settings`, `@constants/text`
