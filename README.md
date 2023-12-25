<?php

function sortNumbersDescending($numbers) {
    if (empty($numbers)) {
        return [];
    }
    arsort($numbers);
    return $numbers;
}

$numbers = [5, 2, 9, 1, 8];
$sortedNumbers = sortNumbersDescending($numbers);
print_r($sortedNumbers);
