# php-gravatar

## getting started  
``` 
include 'Gravatar.php';  
use Prototypeblocks\Gravatar;  
``` 
## examples  
#### get
``` 
$imageUrl = Gravatar::get('name@example.com');
// $imageUrl is either a profile photo of the user, or the default Gravatar profile photo placeholder
``` 
