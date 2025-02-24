### #Numeric_Data_Types

|Data type|Description|
|---|---|
|BIT(_size_)|A bit-value type. The number of bits per value is specified in _size_. The _size_ parameter can hold a value from 1 to 64. The default value for _size_ is 1.|
|TINYINT(_size_)|A very small integer. Signed range is from -128 to 127. Unsigned range is from 0 to 255. The _size_ parameter specifies the maximum display width (which is 255)|
|BOOL|Zero is considered as false, nonzero values are considered as true.|
|BOOLEAN|Equal to BOOL|
|SMALLINT(_size_)|A small integer. Signed range is from -32768 to 32767. Unsigned range is from 0 to 65535. The _size_ parameter specifies the maximum display width (which is 255)|
|MEDIUMINT(_size_)|A medium integer. Signed range is from -8388608 to 8388607. Unsigned range is from 0 to 16777215. The _size_ parameter specifies the maximum display width (which is 255)|
|INT(_size_)|A medium integer. Signed range is from -2147483648 to 2147483647. Unsigned range is from 0 to 4294967295. The _size_ parameter specifies the maximum display width (which is 255)|
|INTEGER(_size_)|Equal to INT(size)|
|BIGINT(_size_)|A large integer. Signed range is from -9223372036854775808 to 9223372036854775807. Unsigned range is from 0 to 18446744073709551615. The _size_ parameter specifies the maximum display width (which is 255)|
|FLOAT(_size_, _d_)|A floating point number. The total number of digits is specified in _size_. The number of digits after the decimal point is specified in the _d_ parameter. This syntax is deprecated in MySQL 8.0.17, and it will be removed in future MySQL versions|
|FLOAT(_p_)|A floating point number. MySQL uses the _p_ value to determine whether to use FLOAT or DOUBLE for the resulting data type. If _p_ is from 0 to 24, the data type becomes FLOAT(). If _p_ is from 25 to 53, the data type becomes DOUBLE()|
|DOUBLE(_size_, _d_)|A normal-size floating point number. The total number of digits is specified in _size_. The number of digits after the decimal point is specified in the _d_ parameter|
|DOUBLE PRECISION(_size_, _d_)||
|DECIMAL(_size_, _d_)|An exact fixed-point number. The total number of digits is specified in _size_. The number of digits after the decimal point is specified in the _d_ parameter. The maximum number for _size_ is 65. The maximum number for _d_ is 30. The default value for _size_ is 10. The default value for _d_ is 0.|
|DEC(_size_, _d_)|Equal to DECIMAL(size,d)|

**Note:** All the numeric data types may have an extra option: UNSIGNED or ZEROFILL. If you add the UNSIGNED option, MySQL disallows negative values for the column. If you add the ZEROFILL option, MySQL automatically also adds the UNSIGNED attribute to the column.