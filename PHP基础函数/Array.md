### array_walk
****
#### 说明
> 使用用户自定义函数对数组中的每个元素做回调处理

    /**
    * @array [输入的数组]
    * @callback 典型情况下 callback 接受两个参数。array 参数值作为第一个，键名作为第二个
    * @userdata 如果提供了可选参数 userdata，将被作为第三个参数传递给 callback funcname。
    * @return bool
    */
    array_walk(array &$array, callback $callback, [, mixed $userdata = NULL]) : bool