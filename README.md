<?php


/*
Basic Information 
Nickname: Nic's
Name: Nichul Ann A. Negrido
Age: 26
Address: SanPablo, Malolos, Bulacan
Hobbies: Cooking, Watching A Movie, TikTok
Dream Job: Not Sure
Course: Associate in Computer Technology
School: Bulacan Polytechnic College
*/

$me = array(

    "name" => "NIchul Ann A. NEgrido",
    "age" => 26,
    "address" => "SanPablo, Malolos, Bulacan",
    "hobbies" => "Cooking, Watching A Movie, TikTok",
    "dream_job" => "Not Surer",
    "course" => "Associate in Computer Technology",
    "school" => "Bulacan Polytechnic College"
);

echo "My Personal Information\n";
echo "Name: " . $me["name"] . "\n";
echo "Age: " . $me["age"] . "\n";
echo "Address: " . $me["address"] . "\n";
echo "Hobbies: " . $me["hobbies"] . "\n";
echo "Dream Job: " . $me["dream_job"] . "\n";
echo "Course: " . $me["course"] . "\n";
echo "School: " . $me["school"] . "\n\n";

print "I am " . $me["name"] . ", a " . $me["course"] . " student of " . $me["school"] . ".";

?>
