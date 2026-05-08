# Main Topic

##   function getSelectedBase() {
        for (let radio of radioButtons) {
          if (radio.checked) return parseInt(radio.value, 10);
        }
        return 10;
      }

## const radioButtons = document.querySelectorAll('input[name="inputBase"]');


##       function updateBadge() {
        const base = getSelectedBase();
        if (base === 2) inputBaseBadge.innerText = "BIN";
        else if (base === 8) inputBaseBadge.innerText = "OCT";
        else if (base === 16) inputBaseBadge.innerText = "HEX";
        else inputBaseBadge.innerText = "DEC";
      }

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 

## 