# 12
#include <iostream>
int main() {
  for (int x = 1, n = 9; n > 0; n--) {
    std::cout << "第" << n << "天吃之前有" << (x + 1) * 2 << "个桃子"
              << std::endl;
    std::cout << "第" << n << "天吃完后有" << x << "个桃子" << std::endl;
    x = (x + 1) * 2;
  }
  return 0;
}
