# ARToolKit Barcode Markers Gallery
This is a collection of ready-to-use Barcode Markers for ARToolKit.

Each Barcode Marker has been made in two resolutions:
- 72dpi - meant to be displayed on screens
- 300dpi - meant to be printed


### How to use it
To use the marker in ARToolKit, the following code must be included in ARToolKit setup keeping in mind the size and the correction algorithm of the used Barcode Marker.

##### 3x3
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`

##### 3x3 Parity(6,5)
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_3x3_PARITY65);`

##### 3x3 Hamming(6,3)
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_3x3_HAMMING63);`

##### 4x4
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_4x4);`

##### 4x4 BCH(13,9,3)
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_4x4_BCH_13_9_3);`

##### 4x4 BCH(13,5,5)
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_4x4_BCH_13_5_5);`

##### 5x5
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_5x5);`

##### 5x5 BCH(22,12,5)
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_5x5_BCH_22_12_5);`

##### 5x5 BCH(22,7,7)
`arSetPatternDetectionMode(<#ARHandle handle#>, AR_MATRIX_CODE_DETECTION);`
`arSetMatrixCodeType(<#ARHandle handle#>, AR_MATRIX_CODE_5x5_BCH_22_7_7);`


### Available Markers
| Matrix code type                      | Folder name                 | Max Available Markers      |
| ------------------------------------- | --------------------------  | -------------------------- |
| AR\_MATRIX\_CODE\_3x3                 | 3x3                         | 64                         |
| AR\_MATRIX\_CODE\_3x3\_PARITY65       | 3x3\_Parity\_6\_5           | 32                         |
| AR\_MATRIX\_CODE\_3x3\_HAMMING63      | 3x3\_Hamming\_6\_3          | 8                          |
| AR\_MATRIX\_CODE\_4x4                 | 4x4                         | 8192                       |
| AR\_MATRIX\_CODE\_4x4\_BCH\_13\_9\_3  | 4x4\_BCH\_13\_9\_3          | 512                        |
| AR\_MATRIX\_CODE\_4x4\_BCH\_13\_5\_5  | 4x4\_BCH\_13\_5\_5          | 32                         |
| AR\_MATRIX\_CODE\_5x5                 | 5x5                         | 4194304                    |
| AR\_MATRIX\_CODE\_5x5\_BCH\_22\_12\_5 | 5x5\_BCH\_22\_12\_5         | 4096                       |
| AR\_MATRIX\_CODE\_5x5\_BCH\_22\_7\_7  | 5x5\_BCH\_22\_7\_7          | 128                        |

