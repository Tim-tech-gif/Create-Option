# Create-Option
use rand::Rng; // Для генерації випадкових чисел use std::cmp;  fn gen_random_vector(n: usize) -> Vec&lt;i32> {     let mut rng = rand::thread_rng();     (0..n).map(|_| rng.gen_range(10..100)).collect() }  fn min_adjacent_sum(data: &amp;[i32]) -> Option&lt;(i32, i32, i32)> {     if data.len() &lt; 2 {         
