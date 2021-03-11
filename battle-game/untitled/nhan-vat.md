---
description: 'Thông tin, lệnh liên quan'
---

# Nhân vật

Bạn cần trang bị một nhân vật và weapon để có thể tham gia trận chiến.

## Các lệnh liên quan

*  Chi tiết nhân vật: `catc [ID]`
*  Thu thập: `catc c`
*  Sử dụng: `catc use [ID]`
*  Đổi tên nhân vật: `catc rn [ID] [tên]`
*  Dùng 3 nhân vật hiện có để đổi lại một nhân vật mới: `catc rr [ID] [ID] [ID]`
*  Nâng cấp nhân vật: `catup c [ID nhân vật] [ID gem] [số lượng gem]`
*  Bán nhân vật: `catsell c [ID] [số lượng]`

{% hint style="info" %}
Xem đầy đủ các lệnh và thông tin chi tiết liên quan: **`cath c`**
{% endhint %}

## Thông tin và chỉ số nhân vật

Để xem đầy đủ chi tiết nhân vật: `catc i [ID]`   
Xem thông tin nhân vật bạn đang có: `catc [ID]`

Các chỉ số:

* Chỉ số cơ bản:  `health` và `mana` sẽ tăng mỗi khi bạn lên level nhân vật
* Chỉ số mở rộng theo thứ tự:  `attack` `defense` `luck` `wisdom` sẽ tăng khi bạn dùng gem nâng cấp \(max +10\) không tăng lên mỗi khi nhân vật bạn lên cấp.

Hệ của mỗi nhân vật sẽ ảnh hưởng tới chỉ số của nhân vật đó.  


{% tabs %}
{% tab title="catc i \[ID\]" %}
Ví dụ xem thông tin nhân vật **Doramiga**. Bạn có thể xem bằng lệnh `catc i 60` hoặc `catc i Doramiga`

![Th&#xF4;ng tin nh&#xE2;n v&#x1EAD;t ID Doramiga](../../.gitbook/assets/image%20%285%29.png)
{% endtab %}

{% tab title="catc \[ID\]" %}
Bằng lệnh này bạn có thể xem chi tiết chỉ số được cộng thêm sau khi lên cấp và nâng cấp, số lượng hiện có của một nhân vật.

![Th&#xF4;ng tin Doramiga b&#x1EA1;n &#x111;ang s&#x1EDF; h&#x1EEF;u](../../.gitbook/assets/image%20%286%29.png)
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Flag tìm kiếm: **-n** tên, **-g** hệ, **-d** miêu tả, **-p** premium \(0,1\), **-e** emoji, **-sr** tỉ lệ xuất hiện, **-a** hiện tất cả.
{% endhint %}



