# resume
my resume😁
header("Content-Length: " . filesize ('https://github.com/kritik-sah/resume/blob/main/2021/kritiksah-resume-2021.pdf' ) ); 
header("Content-type: application/pdf"); 
header("Content-disposition: inline;     
filename=".basename('https://github.com/kritik-sah/resume/blob/main/2021/kritiksah-resume-2021.pdf'));
header('Expires: 0');
header('Cache-Control: must-revalidate, post-check=0, pre-check=0');
$filepath = readfile('https://github.com/kritik-sah/resume/blob/main/2021/kritiksah-resume-2021.pdf');
