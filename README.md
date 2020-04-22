# UI / UX Reference

## Consept 
A html `index.html` is a home for all the image and its related reference text. 
The structure of the `index.html` is simple. 
*  there is table with two columns 
    * Columne 1 for the images
    * column 2 for its description 


## Added new image
To add new image and its description follow steps given below. 

1. Upload your image
1. Edit index.html
1. Copy folllowing code 
    ```html
        <tr>
          <td>
            <img src="" alt="">
          </td>
          <td>
    		Image Description Here
    	  </td>
        </tr>
    ```
1. Past it just before table closing tag i.e. `</table>`
1. In the `<img>` tag update the `src` proparty to have image name
1. Update your description in the 2nd column by replacing "_Image Description Here_" text
