# mlx90615-iio
MLX90615 kernel iio driver, i2c address 0x5b
## prerequisites
```bash sudo apt-get install dkms git ```
## clone repository
```bash git clone https://github.com/shpi/mlx90615-iio ```
## install
```bash cd mlx90615-iio sudo ln -s /home/pi/mlx90615-iio /usr/src/mlx90615-1.0 sudo dkms install mlx90615/1.0 sudo dtc -I dts -O dtb -o 
/boot/overlays/touch.dtbo touch.dts ```