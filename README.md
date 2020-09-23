# Direct-Memory-access-For-stm32f103 
_________________________________________________________________________
using static configuration in the DMA_Config.h file you can set configuration 
_________________________________________________________________________

     
**ALL POSIABLE CONFIGURATION**              

>>>> ENABLE OR DISBALE CHANNEL  
1- DMA_ENABLE_CHANNEL                  
2- DMA_DISABLE_CHANNEL                  

>>>> PRIORITY CONFIGURATION
 1- DMA_CHANNEL_PRIORITY_LOW            
 2- DMA_CHANNEL_PRIORITY_MEDIUM         
 3-  DMA_CHANNEL_PRIORITY_HIGH           
 4- DMA_CHANNEL_PRIORITY_VERY_HIGH      
>>>> PERIPHERAL AND MEMORY SIZE SELECTION *
 1-DMA_MEMORY_PERIHPHERAL_SIZE_8       
 2-DMA_MEMORY_PERIHPHERAL_SIZE_16      
 3-DMA_MEMORY_PERIHPHERAL_SIZE_32      
>>> INCREMENT MODE
 1-DMA_MEMORY_INCREMANT_ENABLE         
 2-DMA_MEMORY_INCREMANT_DISABLE        
 3- DMA_PERIPHERAL_INCREMANT_ENABLE     
 4-DMA_PERIPHERAL_INCREMANT_DISABLE    
 >>>> DMA_CIRCULAR_ENABLE                 
 DATA DIRECTION 
 1-DMA_DATA_DIRECTION_READ_FROM_PERIPHERAL 
 2- DMA_DATA_DIRECTION_READ_FROM_MEMORY     

_______________________________________________________________






## APIs  
1- void MDMA_voidChannelInit(void)  

2- void MDMA_voidEnableInterrupt (u8 Copy_u8ChanelID ,u8 Copy_u8Interrupt)  

3- void MDMA_voidDisableInterrupt (u8 Copy_u8ChanelID ,u8 Copy_u8Interrupt) 

4- void MDMA_voidChannelStart(U8 Copy_u8ChannelID ,u32 * Copy_Pu32peripheralAdd, u32 * Copy_Pu32MemorAdd,u16 Copy_u16BlockLen) 

