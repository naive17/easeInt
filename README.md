# easeInt
 
instance an easy to ease integer without requiring gsap or heavy libraries.

    import easeInt from 'easeint'


    let test = easeInt(100,{duration : 1000,
                            type : 'easeOutCubic',
                            update : (value)=>{
                                console.log('updated value',value)
                            }})


    //update the value 
    test.value = 500;

    //read the value
    console.log(test.value);
