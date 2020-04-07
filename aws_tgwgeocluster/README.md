
Here some variable you should change to your own value. Remember to change it or the terraform will fail

#Please use your own key to create a password hash and copy it to here.
variable "key_name" {
    default = "Use Your Key"
}

variable "sickey" {
    default = "vpn12345"
}

#Please use "openssl passwd -1" to create a password hash and copy it to here.
variable "password_hash" {
    default = "xxxxxxxxxxxx"
}
