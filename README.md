body, h1, h2, p {
	margin: 0;
	padding: 0;
  }
  
  header {
	background-color: #333;
	color: white;
	text-align: center;
	padding: 20px 0;
  }
  
  header h1 {
	font-size: 28px;
  }
  
    .menu {
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between;
	padding: 20px;
  }
  
.menu-items {
	width: calc(33.33% - 20px);
	margin-bottom: 20px;
	padding: 20px;
	background-color: #f7f7f7;
	border: 1px solid #ddd;
	box-sizing: border-box;
  }
  
  .menu-items h2 {
	color: #e74c3c; 
  }
  
  .menu-items p {
	margin-top: 10px;
  }
  
  @media screen and (max-width: 768px) {
	.menu-items {
	  width: 100%;
	}
  }

