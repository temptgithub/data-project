# data-project

function stringCounter(str) {

    if ( typeof str == 'undefined' || str.length < 1 || str === null ) {
         return     console.log( -1);
    }  else if  (str === true || str === false ) {
         return    console.log( -1);
    }

    if ( Array.isArray(str) ) {
            return   console.log(` The amount of items in array is : ${str.length} `);
    }  else if (typeof str  === 'object') {
            return   console.log( ` The number items in object is
    ${Object.keys(str).length} ` );
}


return console.log( `The length of the string is ${str.length} ` );
}
// let str = {"a":1,"b":2,"c":3,"d":4,"e":5,"f":6} ;
// let str = ["a","b","c"];
// let str = 'werqwrwer';
//   stringCounter(str ) ;

