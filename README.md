# Tic-Tac-Toe

let ticTacToe = {

    board : [ [null , null, null] ,[null , null, null],[null , null, null] ],

    move : function( p, rowNum, colNum){
        if (!this.board[rowNum][colNum]){
            this.board[rowNum][colNum] = p
        }
        console.log(this.board)
        return this.board
    },

    clear : function(){
        this.board = [ [null , null, null] ,[null , null, null],[null , null, null] ]
    ,
    console.log(this.board)
    return this.board
    }
}
