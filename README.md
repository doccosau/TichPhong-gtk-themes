# TichPhong Theme
[Tiếng Việt](#tiếng-việt) | [English](#english)

---

## Tiếng Việt

TichPhong Theme là bộ giao diện (GTK theme) chính thức dành cho **TichPhong OS**, mang đến trải nghiệm hiện đại, chuyên nghiệp và đậm đà bản sắc văn hóa thông qua hệ thống màu sắc được lấy cảm hứng từ hệ sinh thái Nhạc Quán. 

Theme hỗ trợ toàn diện từ **GTK 2, GTK 3 cho đến GTK 4** (bao gồm cả libadwaita) và GNOME Shell, tương thích tốt với các môi trường desktop hiện đại như GNOME, XFCE, Mate, v.v.

Bộ theme này được phát triển dựa trên nền tảng của Vimix (vinceliuice) và Materia (nana-4). Xin gửi lời cảm ơn chân thành đến các tác giả gốc.

### Phiên bản màu sắc (Variants)

TichPhong Theme cung cấp 36 biến thể: 6 màu nhấn x 3 chế độ màu x 2 mật độ giao diện.

- **Jade (Xanh ngọc)** - *Mặc định*: Thanh tao, nhẹ nhàng.
- **Cinnabar (Đỏ chu sa)**: Nhiệt huyết, cổ điển.
- **Zen (Nâu thiền)**: Điềm tĩnh, mộc mạc.
- **Mystic (Xám huyền bí)**: Hiện đại, tối giản.
- **Purple (Tím)**: Sáng tạo, mộng mơ.
- **Tet (Tết)**: Đỏ vàng rực rỡ, mang không khí lễ hội.

Mỗi màu có các chế độ `standard`, `light`, `dark` và kích thước `standard`, `compact`. Theme mặc định khuyến nghị cho TichPhong OS là `TichPhong-light-jade`.

### Cài đặt yêu cầu (Dependencies)

**GTK+ 3.20 hoặc mới hơn**
- `sassc`

**GTK2 engines**
- GTK2 engine Murrine 0.98.1.1 hoặc mới hơn.
- GTK2 pixbuf engine hoặc gói `gtk(2)-engines`.

**Ubuntu/Mint/Debian (TichPhong OS):**
```sh
sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf sassc
```

### Hướng dẫn cài đặt

Bạn có thể chạy script cài đặt trực tiếp từ terminal:

```sh
./install.sh
```

**Tùy chọn dòng lệnh (Options):**

```
-d, --dest DIR          Chỉ định thư mục cài đặt (Mặc định: $HOME/.themes)
-n, --name NAME         Chỉ định tên theme (Mặc định: TichPhong)
-t, --theme VARIANT     Chỉ định màu sắc [jade|cinnabar|zen|mystic|purple|tet|all] (Mặc định: jade)
-c, --color VARIANT     Chỉ định biến thể [standard|light|dark] (Mặc định: Tất cả)
-s, --size  VARIANT     Chỉ định kích thước [standard|compact|all] (Mặc định: standard)

-l, --libadwaita        Liên kết theme GTK-4.0 vào thư mục config để áp dụng cho các ứng dụng libadwaita

-r, --remove,
-u, --uninstall         Gỡ cài đặt theme

-tweaks, --tweaks       Chỉ định các tùy chỉnh thêm [flat|zen|mix|translucent]
                        1. flat         Nút điều khiển cửa sổ phẳng
                        2. zen          Nút điều khiển cửa sổ phong cách Zen
                        3. mix          Pha trộn màu theme và Zen tối cho nền ở chế độ Dark
                        4. translucent  Phiên bản panel trong suốt

-h, --help              Hiển thị trợ giúp
```

**Ví dụ:** Cài đặt tất cả phiên bản màu sắc và kích thước:

```sh
./install.sh -t all -s all
```

**Ví dụ:** Cài theme mặc định khuyến nghị:

```sh
./install.sh -t jade -c light -s standard
```

### Đóng góp và Phát triển

TichPhong Theme là một phần của dự án mã nguồn mở **TichPhong OS**. Chúng tôi hoan nghênh mọi đóng góp để cải thiện hệ sinh thái phần mềm Việt Nam.

---

## English

TichPhong Theme is the official GTK theme for **TichPhong OS**, offering a modern, professional experience enriched with cultural identity through a color system inspired by the Nhac Quan ecosystem.

The theme comprehensively supports **GTK 2, GTK 3, and GTK 4** (including libadwaita) as well as GNOME Shell. It is highly compatible with modern desktop environments such as GNOME, XFCE, Mate, etc.

This theme is developed based on Vimix (vinceliuice) and Materia (nana-4). Sincere thanks to the original authors.

### Color Variants

TichPhong Theme provides 36 variants: 6 accent colors x 3 color modes x 2 UI densities.

- **Jade** - *Default*: Elegant and gentle.
- **Cinnabar**: Enthusiastic and classic.
- **Zen**: Calm and rustic.
- **Mystic**: Modern and minimalist.
- **Purple**: Creative and dreamy.
- **Tet**: Vibrant red and yellow, bringing a festive atmosphere.

Each accent includes `standard`, `light`, `dark` modes and `standard`, `compact` sizes. The recommended default for TichPhong OS is `TichPhong-light-jade`.

### Dependencies

**GTK+ 3.20 or later**
- `sassc`

**GTK2 engines**
- GTK2 engine Murrine 0.98.1.1 or later.
- GTK2 pixbuf engine or the `gtk(2)-engines` package.

**Ubuntu/Mint/Debian (TichPhong OS):**
```sh
sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf sassc
```

### Installation

You can run the installation script directly from the terminal:

```sh
./install.sh
```

**Command Line Options:**

```
-d, --dest DIR          Specify destination directory (Default: $HOME/.themes)
-n, --name NAME         Specify theme name (Default: TichPhong)
-t, --theme VARIANT     Specify theme color variant(s) [jade|cinnabar|zen|mystic|purple|tet|all] (Default: jade)
-c, --color VARIANT     Specify color variant(s) [standard|light|dark] (Default: All variants)
-s, --size  VARIANT     Specify size variant [standard|compact|all] (Default: standard)

-l, --libadwaita        Link installed gtk-4.0 theme to config folder to apply for libadwaita apps

-r, --remove,
-u, --uninstall         Uninstall/Remove installed themes

-tweaks, --tweaks       Specify additional tweaks [flat|zen|mix|translucent]
                        1. flat         Flat window control buttons
                        2. zen          Zen-style window control buttons
                        3. mix          Mix theme color and dark Zen tone for background in Dark mode
                        4. translucent  Translucent panel version

-h, --help              Show help
```

**Example:** Install all color and size variants:

```sh
./install.sh -t all -s all
```

**Example:** Install the recommended default theme:

```sh
./install.sh -t jade -c light -s standard
```

### Contribution and Development

TichPhong Theme is an integral part of the **TichPhong OS** open-source project. We welcome all contributions to improve the Vietnamese software ecosystem.
