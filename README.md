# Smart-Palletizer-Robot-Interface
Project: Smart Palletizer with Robot Interface

此專案包含兩個 Python 堆疊模擬程式，皆具備 3D 視覺化與物理支撐檢測功能。

uniform_pattern_palletizer.py:

適用於 單一箱號 (Single SKU) 的大量堆疊。

自動切換「標準圍牆 (Hollow Ring)」與「風車型 (Pinwheel)」演算法。

適合快速計算標準棧板樣式。

dynamic_mixed_palletizer.py:

適用於 混合箱號 (Mixed SKU) 的動態堆疊。

具備 機械手臂整合 (Robot Integration) 功能，可匯出 XYZ 座標 CSV。

核心邏輯：強制條碼朝外 (Barcode Out)、磁吸填縫 (Snap-to-edge)、物理穩定性檢測。
