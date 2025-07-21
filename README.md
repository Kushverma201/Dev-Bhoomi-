<!doctype html>
<html>
     <head>
	      <style>	
                .akhand {
						background-color: white;
						}
	      
				.div1 {
                      border: 1px solid #35B34A;
                      background-color: #35B34A;
					  width: 100%;
					  height: 4%;
					  color: white;
					  margin-top: -1%;
					  margin-left	: -1%;
					  text-align: center;
					  font-size: 15px;
					  font-family: Verdana, Geneva, Tahoma, sans-serif;
					  border-radius: 5px;
					  padding: 1%;
					  }					  			
					  
				.imgs {
					  position: fixed;
					  z-index: 1000;
					  cursor: pointer;
					  }	   					 	
					  
			    .nav1 {
					  position: fixed;
					  left: 40%;
					  top: 9%;
					  z-index: 1000;
					  letter-spacing: 2px ; 
					  }
					  
				.nav1 a {
						text-decoration: none;
						}
						
				.dropdown {
						  position: relative;
						  display: inline-block;
						  }
  
				.dropdown-content {
								  display: none;
								  position: absolute;
								  background-color: #35B34A;
								  min-width: 160px;
								  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
								  z-index: 1;
								  }
  
				.dropdown-content a {
									color: black;
									padding: 12px 16px;
									text-decoration: none;
									display: block;
									}
  
				.dropdown-content a:hover {background-color: white;}
  
				.dropdown:hover .dropdown-content {display: block;}
		
				.dropdown:hover .nav1{background-color: white}
	

				.b1 {    
					position: fixed;
					border: 1px solid #35B34A;
				    color: white;
				    font-size: 20px;
				    background-color: #35B34A;
				    width: 15%;
				    left: 10px;
				    text-align: center;
				    padding: 3px;
				    margin-left: 85%;
				    margin-top: 1%;
				    border-radius: 20px;
					}
					
				.b1:hover {
						  background-color: #35B34A;
						  position: relative;
				          display: inline-block;
						  }	
						  
				.width {
					   margin-top: 5%;
					   }		  

                .logo {
					  font-size: 70px;
					  margin-top: -40%;
					  margin-left: 5%;
					  }	

                .logo0 {
			           margin-top: 3%;
					   margin-left: 5%;
					   font-size: 20px;
				       color: #909090;
				       font-family: sans-serif;
				       }	

                .logo1 {
				       font-size: 25px;
					   margin-top: 5%;
					   margin-left: 5%;
					   }	

                .logo2 {
					   border: 1px solid #35B34A;
				       color: white;
				       font-size: 20px;
				       background-color: #35B34A;
				       width: 10%;
				       left: 10px;
				       text-align: center;
				       padding: 10px;
				       margin-left: 5%;
				       margin-top: 5%;
				       border-radius: 20px;
				       } 
					   
			    .logo2 {
				       position: relative;
				       display: inline-block;
				       }

                .div30 {
					   position: relative;
					   margin-top: -10%;
					   left: 76%;
					   width: 190px;
					   height: 190px;
					   transform: rotate(30deg);
					   border:none;
					   background-color:  #35B34A;
					   }

				.div31 {
					   position: relative;
					   margin-top: -13%;
					   left: 76%;
					   width: 190px;
					   height: 190px;
					   transform: rotate(60deg);
					   border: none;
					   background-color:  #35B34A;
					   }

				.div32 {
					   position: relative;
					   margin-top: -13%;
					   left: 76%;
					   width: 190px;
					   height: 190px;
					   transform: rotate(-90deg);
					   border: none;
					   background-color:  #35B34A;
					   }

				.div33 {
					   position: relative;
					   margin-top: -10%;
					   left: 76.5%;
					   width: 160px;
					   height: 160px;
					   border: none;
					   background-color:  #35B34A;
					   }

				.chat1 {
					   position: relative;
					   margin-top: -100%;
					   left: 4%;
					   color: white;
					   font-size: 18px;
					   font-family: Verdana, Geneva, Tahoma, sans-serif;
					   }
	
				.text1 {
					   position: relative;
					   top: -5%;
					   left: 39%;
					   color: white;
					   font-size: 19px;
					   font-family: Verdana, Geneva, Tahoma, sans-serif;
					   }

				.num {
					 position: relative;
					 top: -8%;
					 left: 14%;
					 color: white;
					 font-size: 25px;
					 }
					 
				.num:hover {
						   color: blue;
						   cursor: pointer;
						   }	               

               /*banner starts*/
			   .bg {
				   height: 600px;
				   width: 110%;
				   border:none;
				   background-image:url('../image/bg.png');
				   }
				
			   .we {
			       color: white;
				   font-size: 68px;
				   font-weight: bold;
				   margin-left: 50%;
				   margin-top: -6%;
				   font-family: 'Montserrat', sans-serif;
				   }
				
			   .give {
				     font-size: 24px;
				     color: orange;
				     font-weight: 600;
				     margin-left: 45%;
				     margin-top: 3%;
				     font-family: 'Montserrat', sans-serif;
				     }
				  
			   .real {
			         color: black;
				     font-size: 24px;
				     font-weight: 600;
					 color: orange;
				     margin-left: 29%;
				     margin-top: -0.5%;
				     font-family: 'Montserrat', sans-serif;
				     }
					   
			  .box {
				   border: 1px solid;
				   background-color: #FFF;
				   height: 200px;
				   width: 19%;
				   margin-left: 15%;
				   margin-top: 3%;
				   border:none;
				   border-radius: 3px;
				   position: absolute;
				   }
				 
			 .box:hover {
					    box-shadow: 0px 4px 25px rgb(192,192,192);
					    }
					   
			 .vector {
					 margin-left: 40%;
					 padding-top: 10%;
					 }
					
			 .look {
				   text-align: center;
				   font-weight: 500;
				   margin-top: 10%;
				   font-size: 18px;
				   letter-spacing: 1px;
				   word-spacing: 1px;
				   font-family: 'Montserrat', sans-serif;
				   }
				  
			 .box1 {
				   border: 1px solid;
				   background-color: #FFF;
				   height: 200px;
				   width: 19%;
				   margin-left: 35%;
				   margin-top: 3%;
				   border:none;
				   border-radius: 3px;
				   position: absolute;
				   }
				  
			 .box1:hover {
						 box-shadow: 0px 4px 25px rgb(192,192,192);
						 } 
						
			 .heart {
				    margin-left: 40%;
				    padding-top: 15%;
				    }
				   
			 .feel {
				   margin-left: 28%;
				   margin-top: 14%;
				   font-weight: 500;
				   letter-spacing: 1px;
				   font-size: 18px;
				   word-spacing: 1px;
				   font-family: 'Montserrat', sans-serif;
				   }
				  
			 .box2 {
				   border: 1px solid;
				   background-color:#FFF;
				   height: 30%;
				   width: 20%;
				   margin-left: 55%;
				   margin-top: 3%;
				   border:none;
				   border-radius: 3px;	
				   position: absolute;
				   }
				  
			 .box2:hover {
						 box-shadow: 0px 4px 25px rgb(192,192,192);
						 }

			 .star {
				   margin-left: 40%;
				   padding-top: 15%;
				   } 
				  
			 .perform {
					  margin-left: 25%;
					  margin-top: 14%;
					  font-weight: 500;
					  font-size: 18px;
					  letter-spacing: 1px;
					  word-spacing: 2px;
					  font-family: 'Montserrat', sans-serif;
					  }	

             .and {
			      margin-top: -20%;
				  margin-left: 5%;
				  font-size: 20px;
				  color: #909090;
				  font-family: sans-serif;
				  }		

             .and0 {
			       margin-top: 3%;
				   margin-left: 5%;
				   font-size: 45px;
				   }	

              .and1 {
			        margin-top: 3%;
				    margin-left: 5%;
				    font-size: 20px;
				    color: #909090;
				    font-family: sans-serif;
				    }
					
			 .svg {
			      margin-top: 5%;
			      margin-left: 5%;
				  width: 25%;
				  height: 100px;
				  background-color: rgba(53,179,74,0.1);
				  border-left: 5px solid #35B34A;
				  }	  

             .svg0 {
				   margin-left: 5%;
				   margin-top: 3%;
				   }	

             .svg1 {
				   margin-top: 0%;
			       margin-left: 5%;
				   width: 25%;
				   height: 100px;
				   }
				   
			 .svg1:hover {
				         background-color: rgba(53,179,74,0.1);
						 border-left: 5px solid #35B34A;
						 }	   

             .svg2 {
				   margin-left: 5%;
				   margin-top: 6%;
				   }

             .svg3 {
				   margin-top: 0%;
			       margin-left: 5%;
				   width: 25%;
				   height: 100px;
				   }
				   
			 .svg3:hover {
				         background-color: rgba(53,179,74,0.1);
						 border-left: 5px solid #35B34A;
						 }	   

             .svg4 {
				   margin-left: 5%;
				   margin-top: 6%;
				   }				   

             .box0 {
				   border: 1px solid;
				   background-color: #FFF;
				   height: 400px;
				   width: 23.3%;
				   margin-left: 35%;
				   margin-top: -22%;
				   border:none;
				   border-radius: 3px;
				   position: absolute;
				   }
				 
			 .box0:hover {
					     box-shadow: 0px 4px 25px rgb(192,192,192);
					     }
					   
			 .vector0 {
					  margin-left: 0%;
					  padding-top: 0%;
					  }
					
			 .look0 {
				    text-align: center;
				    font-weight: 500;
				    margin-top: 5%;
					margin-left: -25%;
				    font-size: 20px;
				    letter-spacing: 1px;
				    word-spacing: 1px;
				    font-family: 'Montserrat', sans-serif;
				    }
					
			 .look1 {
			        margin-top: 2%;
					margin-left: 5%;
					font-size: 15px;
				    color: #909090;
				    font-family: sans-serif;
					}	

             .look2 {
					font-size: 20px;
			        margin-top: 17%;
					margin-left: 5%;
					color: #35B34A;
					}					
				  
			 .box3 {
				   border: 1px solid;
				   background-color: #FFF;
				   height: 400px;
				   width: 23.3%;
				   margin-left: 60%;
				   margin-top: -22%;
				   border:none;
				   border-radius: 3px;
				   position: absolute;
				   }
				  
			 .box3:hover {
						 box-shadow: 0px 4px 25px rgb(192,192,192);
						 } 
						
			 .heart0 {
				     margin-left: 0%;
				     padding-top: 0%;
				     }
				   
			 .feel0 {
				    margin-left: 8%;
				    margin-top: 5%;
				    font-weight: 500;
				    letter-spacing: 1px;
				    font-size: 18px;
				    word-spacing: 1px;
				    font-family: 'Montserrat', sans-serif;
				    }	

             .feel1 {
			        margin-top: 2%;
					margin-left: 5%;
					font-size: 15px;
				    color: #909090;
				    font-family: sans-serif;
					}	

             .feel2 {
					font-size: 20px;
			        margin-top: 10%;
					margin-left: 5%;
					color: #35B34A;
					}

             .game {
				   margin-top: 10%;
				   }

             .game0 {
					font-size: 70px;
					margin-top: -35%;
					margin-left: 2%;
					}	

             .game1 {
			        margin-top: 5%;
					margin-left: 2%;
					font-size: 20px;
				    color: #909090;
				    font-family: sans-serif;
					}

             .game2 {
					border: 1px solid #35B34A;
				    color: white;
				    font-size: 20px;
				    background-color: #35B34A;
				    width: 10%;
				    left: 10px;
				    text-align: center;
				    padding: 10px;
				    margin-left: 5%;
				    margin-top: 8%;
				    border-radius: 20px;
				    } 
					   
			  .game2 {
				     position: relative;
				     display: inline-block;
				     } 

			  .border00 {
			            border: none;
			            background-color:#FFFFFF;
			            width: 1600px;
			            height: 500px;
		                }
					 
		     .ideal00 {
					  margin-left: 3%;
					  margin-top: 15%;
					  font-size: 20px;
					  color: #999999;
					  }
					
		     .heading00 {
				        margin-left: 3%;
				        font-size: 45px;
				        color: #000000;
				        font-family: sans-serif;
				        } 
				 
		     .view00 {
			         margin-left: 87%;
			         font-size: 20px;
			         color: #5bb450;
			         margin-bottom: 5%;
		             }
			  
		     .weight00 {
				       border: none;
				       height: 350px;
				       width: 440px;
				       box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
				       display: inline-block;
			           margin-left: 2%;
  				       margin-bottom: 10%;
				       }
				
		      .the00 {
 			         margin-left: 2%;
			         color :#B4B4B4;
     			     font-family: sans-serif;
			         margin-top: 8%;
			         margin-left: 5%;
				     }
			 
			  .loss00 {
			          margin-left: 2%;
				      color: #000000;
				      font-family: sans-serif;
				      margin-top: 8%;
				      margin-left: 5%;
				      font-size: 45px;
					  }
			  
			  .reset00 {
					   margin-left: 2%;
					   color: #909090;
					   font-family: sans-serif;
					   margin-top: 8%;
					   margin-left: 5%;
					   font-size: 20px;
					   }
					 
		      .learn__00 {
  					     margin-left: 2%;
					     color: #5bb450;
					     font-family: sans-serif;
					     margin-top: 5%;
					     margin-left: 5%;
					     } 
					   
			  .learn__00 {
						 position: relative;
						 display: inline-block;
						 }

			  .learn__00 .img {
							  visibility: hidden;
							  width: 30px;
							  color: #fff;
							  text-align: center;
							  border-radius: 6px;
							  padding: 1px;
							  margin-bottom: -2px;

							  /* Position the tooltip */
							  position: absolute;
							  z-index: 1;
							  }

			 .learn__00:hover .img {
								   visibility: visible;
								   }	
				 
			  .weight100 {
				         border: none;
				         height: 350px;
					     width: 475px;
					     box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
					     display: inline-block;
					     margin-bottom: 10%;
					     float: right;
					     margin-right: 40%;
					     }	 
 				 
		      .second00 {
					    margin-left: 1%;
					    color :#B4B4B4;
					    font-family: sans-serif;
					    margin-top: 8%;
					    margin-left: 5%;
					    }
				
			  .stable00 {
					    margin-left: 2%;
					    color: #000000;
					    font-family: sans-serif;
					    margin-top: 8%;
					    margin-left: 5%;
					    font-size:45px;
					    } 
				
			  .mind00 {
					  margin-left: 2%;
					  color: #909090;
					  font-family: sans-serif;
					  margin-top: 8%;
					  margin-left: 5%;
					  font-size: 20px;
					  }
				   
			  .weight200 {
					     border: none;
					     height: 350px;
					     width: 475px;
					     box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
					     display: inline-block;
					     margin-right: 145px;
					     float: right;
					     margin-top: -32%;
					     }
				 
			  .third00 {
					   margin-left: 1%;
					   color: #B4B4B4;
					   font-family: sans-serif;
					   margin-top: 8%;
					   margin-left: 5%;
					   }
			   
			  .main00 {
					  margin-left: 2%;
					  color: #000000;
					  font-family: sans-serif;
					  margin-top: 8%;
					  margin-left: 5%;
					  font-size: 45px;
					  }
			  
			  .possible00 {
  						  margin-left: 2%;
						  color: #909090;
						  font-family: sans-serif;
						  margin-top: 8%;
						  margin-left: 5%;
						  font-size: 20px;
						  }  
						
			  .tools {
				     color: #909090;
				     font-family: sans-serif;
					 margin-top: -3%;
					 margin-left: 5%;
					 font-size: 15px;
					 } 	

              .tools0 {
					  font-size: 45px;
					  margin-top: 3%;
					  margin-left: 5%;
					  }	

              .learn__01 {
					     color: #5bb450;
					     font-family: sans-serif;
					     margin-top: -25%;
					     margin-left: 90%;
					     } 
					   
			  .learn__01 {
						 position: relative;
						 display: inline-block;
						 }		

               .tools1 {
					   font-size: 20px;
					   margin-left: 5%;
					   margin-top: 5%;
					   }

              .tools2 {
					   font-size: 50px;
					   color: #35B34A;
					   margin-left: 5%;
					   margin-top: 5%;
					   }	

              .tools3 {
					  margin-top: 5%;
					  margin-left: 5%;
					  color: #909090;
				      font-family: sans-serif;
					  }	

              .learn__02 {
					     color: #35B34A;
					     font-family: sans-serif;
					     margin-top: 5%;
					     margin-left: 5%;
					     } 
					   
			  .learn__02 {
						 position: relative;
						 display: inline-block;
						 }	

              .tools4 {
					  margin-left: 35%;
					  margin-top: -32%;
					  }	
     
              .tools5 {
					  margin-left: 2%;
					  margin-top: 2%;
					  }	

               .tools6 {
					   font-size: 20px;
					   margin-left: 65%;
					   margin-top: -38%;
					   }

              .tools7 {
					   font-size: 50px;
					   color: #35B34A;
					   margin-left: 65%;
					   margin-top: 5%;
					   }	

              .tools8 {
					  margin-top: 5%;
					  margin-left: 65%;
					  color: #909090;
				      font-family: sans-serif;
					  }	

              .learn__03 {
					     color: #35B34A;
					     font-family: sans-serif;
					     margin-top: 5%;
					     margin-left: 65%;
					     } 
					   
			  .learn__03 {
						 position: relative;
						 display: inline-block;
						 }	

               .bordergg {
			             border: none;
			             background-color:#FFFFFF;
			             width: 1600px;
			             height: 500px;
		                 }
					 
		     .idealgg {
					  margin-left: 5%;
					  margin-top: 10%;
					  font-size: 20px;
					  color: #999999;
					  }
					  
			 .idealpp {
					  margin-left: 5%;
					  }		  
					
		     .headinggg {
				        margin-left: 1%;
				        font-size: 45px;
				        color: #000000;
				        font-family: sans-serif;
				        } 
				 
		     .viewgg {
			         margin-left: 87%;
			         font-size: 20px;
			         color: #5bb450;
			         margin-bottom: 5%;
		             }
			  
		     .weightgg {
  				       border: none;
				       height: 380px;
				       width: 610px;
				       box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
				       display: inline-block;
			           margin-left: 2%;
  				       margin-bottom: 10%;
				       }
				
		      .thegg {
 			         margin-left: 2%;
			         color :#B4B4B4;
     			     font-family: sans-serif;
			         margin-top: 8%;
			         margin-left: 5%;
				     }
			 
			  .lossgg {
			          margin-left: 2%;
				      color: #000000;
				      font-family: sans-serif;
				      margin-top: 8%;
				      margin-left: 5%;
				      font-size: 25px;
					  }
					  
			  .king {
					border-radius: 30px;
					}	  
			  
			  .resetgg {
					   margin-left: 2%;
					   color: #909090;
					   font-family: sans-serif;
					   margin-top: 8%;
					   margin-left: 3%;
					   font-size: 18px;
					   }
					 
		      .learn__gg {
 					     margin-left: 2%;
					     color: #5bb450;
					     font-family: sans-serif;
					     margin-top: 5%;
					     margin-left: 5%;
					     } 
					   
			  .learn__gg {
						 position: relative;
						 display: inline-block;
						 }

			  .learn__gg .img {
							  visibility: hidden;
							  width: 30px;
							  color: #fff;
							  text-align: center;
							  border-radius: 6px;
							  padding: 1px;
							  margin-bottom: -2px;

							  /* Position the tooltip */
							  position: absolute;
							  z-index: 1;
							  }

			 .learn__gg:hover .img {
								   visibility: visible;
								   }		   
				 
			  .weight1gg {
				         border: none;
				         height: 380px;
					     width: 600px;
					     box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
					     display: inline-block;
					     margin-left: 6%;
					     margin-bottom: 20%;
					     float: right;
					     margin-right: 15%;
					     }	 
				 
		      .secondgg {
					    margin-left: 1%;
					    color :#B4B4B4;
					    font-family: sans-serif;
					    margin-top: 8%;
					    margin-left: 5%;
					    }
				
			  .stablegg {
					    margin-left: 2%;
					    color: #000000;
					    font-family: sans-serif;
					    margin-top: 8%;
					    margin-left: 5%;
					    font-size: 25px;
					    } 
				
			  .king0 {
					 border-radius: 30px;
					 } 	
				
			  .mindgg {
					  margin-left: 2%;
					  color: #909090;
					  font-family: sans-serif;
					  margin-top: 8%;
   					  margin-left: 2%;
					  font-size: 17px;
					  }
			   
			  .learn1__gg {
  						  margin-left: 2%;
						  color: #5bb450;
						  font-family: sans-serif;
						  margin-top: 5%;
						  margin-left: 5%;
						  }

            .border55 {
			          border: none;
			          background-color:#FFFFFF;
			          width: 1600px;
			          height: 500px;
		              }
					 
		     .ideal55 {
					  margin-left: 5%;
					  margin-top: -0%;
					  font-size: 20px;
					  color: #999999;
					  }
					  
			 .ideal66 {
					  margin-left: 5%;
					  }		  
					
		     .heading55 {
				        margin-left: 1%;
				        font-size: 45px;
				        color: #000000;
				        font-family: sans-serif;
				        } 
				 
		     .view55 {
			         margin-left: 87%;
			         font-size: 20px;
			         color: #5bb450;
			         margin-bottom: 5%;
		             }
			  
		     .weight55 {
  				       border: none;
				       height: 380px;
				       width: 610px;
				       box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
				       display: inline-block;
			           margin-left: 2%;
  				       margin-bottom: 10%;
				       }
				
		      .the55 {
 			         margin-left: 2%;
			         color :#B4B4B4;
     			     font-family: sans-serif;
			         margin-top: 8%;
			         margin-left: 5%;
				     }
			 
			  .loss55 {
				      color: #000000;
				      font-family: sans-serif;
				      margin-top: 6%;
				      margin-left: 5%;
				      font-size: 25px;
					  }
					  
			  .king55 {
					  border-radius: 30px;
					  }	  
			  
			  .reset55 {
					   margin-left: 2%;
					   color: #909090;
					   font-family: sans-serif;
					   margin-top: 8%;
					   margin-left: 3%;
					   font-size: 18px;
					   }
					 
		      .learn__55 {
 					     margin-left: 2%;
					     color: #5bb450;
					     font-family: sans-serif;
					     margin-top: 5%;
					     margin-left: 5%;
					     } 
					   
			  .learn__55 {
						 position: relative;
						 display: inline-block;
						 }

			  .learn__55 .img {
							  visibility: hidden;
							  width: 30px;
							  color: #fff;
							  text-align: center;
							  border-radius: 6px;
							  padding: 1px;
							  margin-bottom: -2px;

							  /* Position the tooltip */
							  position: absolute;
							  z-index: 1;
							  }

			 .learn__55:hover .img {
								   visibility: visible;
								   }		   
				 
			  .weight155 {
				         border: none;
				         height: 380px;
					     width: 600px;
					     box-shadow: 0px 4px 30px 0px rgba(154,154,154,0.25);
					     display: inline-block;
					     margin-left: 6%;
					     margin-top: -33.5%;
					     float: right;
					     margin-right: 15%;
					     }	 
				 
		      .second55 {
					    margin-left: 1%;
					    color :#B4B4B4;
					    font-family: sans-serif;
					    margin-top: 8%;
					    margin-left: 5%;
					    }
				
			  .stable55 {
					    margin-left: 2%;
					    color: #000000;
					    font-family: sans-serif;
					    margin-top: 8%;
					    margin-left: 5%;
					    font-size: 25px;
					    } 
				
			  .king50 {
					  border-radius: 30px;
					  } 	
				
			  .mind55 {
					  margin-left: 2%;
					  color: #909090;
					  font-family: sans-serif;
					  margin-top: 8%;
   					  margin-left: 2%;
					  font-size: 17px;
					  }
			   
			  .learn1__55 {
  						  margin-left: 2%;
						  color: #5bb450;
						  font-family: sans-serif;
						  margin-top: 5%;
						  margin-left: 5%;
						  }	

              .logos {
					 background-image: url(image/logos.png);
					 margin-top: 40%;
					 }						  

              .main {
					font-size: 170px;
					margin-top: -45%;
				    margin-left: 5%;
					color: white;
					}
					
			  .main1 {
					 font-size: 30px;
					 margin-top: 2%;
				     margin-left: 5%;
					 color: white;
					 }
					 
			 .main2 {
				    border: 2px solid white;
					color: white;
					width: 10%;
					left: 20px;
					text-align: center;
					padding: 10px;
					margin-left: 4%;
					margin-top: 10%;
					border-radius: 20%:
					}

			 .main3 {
					border: 2px solid white;
					color: white;
					width: 15%;
					left: 20px;
					text-align: center;
				    padding: 10px;
					margin-left: 18%;
					margin-top: -3%;
					border-radius: 20%:	 
					}
					
			 .main2:link {
						 color: green;
						 border-color: green;
						 }  
				  
		     .main2:visited {
							color: green;
							border-color: green;
							}  
						 
			 .main2:hover {
						  color: green;
						  border-color: green;
						  }		  
						
			 .main2:active {
						   color: cyan;
						   border-color: green;
						   }
							 
			 .main3:link {
						 color: green;
						 border-color: green;
						 }  
				  
			 .main3:visited {
							color: green;
							border-color: green;
							}  
						 
			 .main3:hover {
						  color: green;
						  border-color: green;
						  }		  
						
			 .main3:active {
						   color: cyan;
						   border-color: green;
						   }

             .main4 {
					color: #909090;
				    font-family: sans-serif;
					margin-top: 5%;
					margin-left: 5%;
					font-size: 18px;
					}		

             .main5 {
					font-size: 50px;
					margin-left: 5%;
					margin-top: 5%;
					}	

             .main6 {
			        margin-top: 5%;
			        margin-left: 5%;
				    width: 25%;
					font-size: 45px;
				    height: 100px;
					background-color: rgba(53,179,74,0.1);
					border-bottom: 5px solid #35B34A;
				    }  	  

             .main6:hover {						  
						  border-left: 5px solid #35B34A;
						  }	

             .main7 {
				    margin-top: 0%;
			        margin-left: 5%;
				    width: 25%;
					font-size: 40px;
				    height: 100px;
				    }
				   
			 .main7:hover {
				          background-color: rgba(53,179,74,0.1);
						  border-left: 5px solid #35B34A;
						  }	

             .main8 {
				    margin-top: 0%;
			        margin-left: 5%;
				    width: 25%;
					font-size: 40px;
				    height: 100px;
				    }
				   
			 .main8:hover {
				          background-color: rgba(53,179,74,0.1);
						  border-left: 5px solid #35B34A;
						  }	

             .main9 {
				    margin-top: 0%;
			        margin-left: 5%;
				    width: 25%;
					font-size: 40px;
				    height: 100px;
				    }
				   
			 .main9:hover {
				          background-color: rgba(53,179,74,0.1);
						  border-left: 5px solid #35B34A;
						  }		

             .main10 {
				    margin-top: 0%;
			        margin-left: 5%;
				    width: 25%;
					font-size: 40px;
				    height: 100px;
				    }
				   
			 .main10:hover {
				          background-color: rgba(53,179,74,0.1);
						  border-left: 5px solid #35B34A;
						  }	

             .main11 {
				    margin-top: 0%;
			        margin-left: 5%;
				    width: 25%;
					font-size: 40px;
				    height: 100px;
				    }
				   
			 .main11:hover {
				          background-color: rgba(53,179,74,0.1);
						  border-left: 5px solid #35B34A;
						  }		

             .end {
				  margin-top: -40%;
				  margin-left: 35%;
				  }					

             .hr {
				 width: 70%;
				 margin-left: -0%;
				 }	

             .end0 {
				   margin-top: 5%;
				   margin-left: -0%;
				   }					

             .hr0 {
				  width: 70%;
				  margin-left: -0%;
				  }	

             .end1 {
				   margin-top: 5%;
				   margin-left: -0%;
				   }					

             .hr1 {
				  width: 70%;
				  margin-left: -0%;
				  }	

             .end2 {
				   margin-top: 5%;
				   margin-left: -0%;
				   }					

             .hr2 {
				  width: 70%;
				  margin-left: -0%;
				  }

             .end3 {
				   margin-top: 5%;
				   margin-left: -0%;
				   }					

             .hr3 {
				  width: 70%;
				  margin-left: -0%;
				  }		

             .plus {
				   margin-left: 50%;
				   }

             .plus0 {
				    margin-left: 40%;
				    } 

             .plus1 {
				    margin-left: 35%;
				    } 

             .plus2 {
				    margin-left: 47%;
				    } 

             .plus3 {
				    margin-left: 54%;
				    } 	

             .png {
				  color: #909090;
				  font-family: sans-serif;
				  margin-top: 10%;
				  margin-left: -45%;
				  font-size: 18px;
				  }			

             .png0 {
				   font-size: 45px;
				   margin-top: 5%;
				   margin-left: -45%
				   }	

             .form1 {
					position: relative;
					margin-top: 10%;
					margin-left: -67%;
					width: 220%;
					}

			 input {
				   position: relative;
				   top: 10%;
				   left: 10%;
				   outline: 0;
				   border-width: 0  0 2px;
				   border-color: black;
				   width: 20%;
				   display: inline-block;
				   }

			input:hover {
						border-color: green;
						}

			.select {
					position: relative;
					top: 10%;
					left: 10%;
					outline: 0;
					border-width: 0  0 2px;
					border-color: black;
					width: 20%;
					display: inline-block;
					}

			.select:hover {
						  border-color: green;
						  color: green;
						  }

			.b6 {
				top: 10%;
				left: 10%;
				width: 7%;
				height: 15%;
				padding: 0.5%;
				border: none;
				background-color: #35B34A;
				color:white;
				font-size: 25px;
				font-family: Verdana, Geneva, Tahoma, sans-serif;
				cursor: pointer;
				}

			.b6:hover {
					  background-color: green;
					  }
					  
			.footer {
					background-color: black;
					margin-left: -54%;
					margin-top: 4%;
					height: 500px;
					}	

            .footer0 {
					 margin-top: 2%;
					 margin-left: 2%;
					 }	

            .footer1 {
					 color: white;
					 margin-left: 50%;
					 margin-top: -2%;
					 }	

            .footer2 {
					 border: 1px solid white;
				     color: white;
					 width: 10%;
					 left: 10px;
					 padding: 10px;
					 margin-left: 83%;
					 margin-top: -2%;
					 border-radius: 20%:
					 }
             						
			 .footer2:hover {
						    color: green;
						    border-color: green;
						    }

             .footer3 {
					  margin-top: 1%;
					  }	

             .footer4 {
					  color: white;
					  margin-top: 3%;
					  margin-left: 5%;
					  }	

             .header {
					 color: white;
					 margin-top: -6.5%;
					 margin-left: 30%;
					 }	

             .header0 {
					  color: #909090;
				      font-family: sans-serif;
					  margin-top: 1%;
					  margin-left: 30%;
					  font-size: 14px;
					  }	

             .week {
				   color: white;
				   margin-top: 1%;
				   margin-left: 30%;
				   }

             .header2 {
					  color: #909090;
				      font-family: sans-serif;
					  margin-top: 3%;
					  margin-left: 30%;
					  font-size: 14px;
					  }

             .header3 {
					  color: white;
					  margin-top: -0%;
					  margin-left: 30%;
					  }	

             .lock {
				   color: white;
				   margin-top: -13.5%;
				   margin-left: 50%;
				   }	

             .lock0 {
					color: white;
				    margin-top: 1%;
				    margin-left: 50%;
					}			

             .lock0:hover {
						  color: green;
						  }	

             .lock1 {
					color: white;
				    margin-top: 0.5%;
				    margin-left: 50%;
					}			

             .lock1:hover {
						  color: green;
						  }

             .lock2 {
					color: white;
				    margin-top: 0.5%;
				    margin-left: 50%;
					}			

             .lock2:hover {
						  color: green;
						  }	

             .lock3 {
					color: white;
				    margin-top: 0.5%;
				    margin-left: 50%;
					}			

             .lock3:hover {
						  color: green;
						  }

             .lock4 {
					color: white;
				    margin-top: 0.5%;
				    margin-left: 50%;
					}			

             .lock4:hover {
						  color: green;
						  }

             .lock5 {
					color: white;
				    margin-top: 0.5%;
				    margin-left: 50%;
					}			

             .lock5:hover {
						  color: green;
						  }	

             .contact {
					  color: white;
				      margin-top: -12.4%;
				      margin-left: 70%;
					  }	

             .contact0 {
					   color: #909090;
				       font-family: sans-serif;
					   margin-top: 1%;
					   margin-left: 70%;
					   font-size: 14px;
					   }

             .contact1 {
					   color: white;
					   margin-top: -1.1%;
					   margin-left: 78%;
					   }

             .contact2 {
					   color: #909090;
				       font-family: sans-serif;
					   margin-top: 1%;
					   margin-left: 70%;
					   font-size: 14px;
					   }

             .contact3 {
					   color: white;
					   margin-top: -1.1%;
					   margin-left: 72.5%;
					   }

             .contact4 {
					   color: #909090;
				       font-family: sans-serif;
					   margin-top: 1%;
					   margin-left: 70%;
					   font-size: 14px;
					   }

             .contact5 {
					   color: white;
					   margin-top: -1.3%;
					   margin-left: 74%;
					   }

             .contact6 {
					   margin-top: 11%;
					   }

             .real {
				   color: #909090;
				   font-family: sans-serif;
				   margin-top: 2%;
				   margin-left: 3%;
				   font-size: 14px;
				   }	
			 
             .real0 {
					color: white;
					margin-left: 80%;
					margin-top: -1%;
					}			 
	      </style>
     </head>
	 <body>
	    <!--header  start-->
	      <div class="div1" >Interested in starting Ideal Protein without paying program start fees? <u>Click here</u> to check out our new dieter specials.</div>
        <!--header end--> 
        <div class="akhand">		
        <img src="image/bio image.png" width="10%" class="imgs">
		     
        <!--nav start-->
 		 <nav class="nav1">
		    <div class="dropdown">
		         <a href="https://biointelligentwellness.com/programs/"><font color="black">Programs</font></a>&nbsp;&nbsp;&nbsp;
		              <div class="dropdown-content">
						<a href="#">Ideal  Protein</a>
						<a href="#">Metabolism Testing</a>
						<a href="#">Customized Nutrition</a>
					  </div>
			</div>
				<a href="https://biointelligentwellness.com/patient-forms/"><font color="black">Patient Form</font></a>&nbsp;&nbsp;&nbsp;
				<a href="https://biointelligentwellness.com/about-us/"><font color="black">About Us</font></a>&nbsp;&nbsp;&nbsp;
			  <div class="dropdown">
				<a href="https://biointelligentwellness.com/b2b/"><font color="black">B2B</font></a>&nbsp;&nbsp;&nbsp;
		      <div class="dropdown-content">
				<a href="#">Provider</a>
				<a href="#"> Corporate Wellness</a>  
			  </div>
			  </div> 
				<a href="https://biointelligentwellness.com/blog/"><font color="black">Blog</font></a>&nbsp;&nbsp;&nbsp;
				<a href="https://biointelligentwellness.com/success-stories/"><font color="black">Success Stories</font></a>&nbsp;&nbsp;&nbsp;
	    </nav>
	   <!--nav end-->	
		
		    <div class="b1"><b>Free Consultation</b></div>		
            </div>
  	        <img src="image/logo.jpg" width="100%" class="width">
				<div class="logo"><b>We can help you</b></div>
				<div class="logo0"> No, seriously!</div>
				<div class="logo1"><b>Give us your worst health problems and we will<br>give you real solutions</b></div>	
				<div class="logo2"><b>Get Started</b></div>
				
			<div class="div30"></div>
			<div class="div31"></div>
			<div class="div32"></div>
			<div class="div33">
			<p class="chat1"><b>Chat with us or </b></p>
			<p class="text1"><b>Text</b></p>
			<p class="num">858-228-3644</p>
			</div>		
			
		 <!--banner section starts-->
			<section class="banner">
				<div class="bg">					
					<div class="box">
						<div class="vector"><img src="image/vector.svg"></div>
						<div class="look">LOOK BETTERS</div><br>						
					</div>
					<div class="box1">
						<div class="heart"><img src="image/heart.svg"></div>
						<div class="feel">FEEL BETTER</div><br>
					</div>	
					<div class="box2">
						<div class="star"><img src="image/star.svg"></div>
						<div class="perform">PERFORM BETTER</div><br>
				    </div>
				</div>
			</section>		
	     <!--banner section ends-->
		 
		 <!--section start-->
		 <section>
				<div class="and">HOW WE HELP</div>
				<div class="and0"><b>Your Goals. Our Programs.<br>Lasting Solutions</b></div>
				<div class="and1">Programs we suggest to you based on your goals</div>
		 
				<div class="svg"><img src="image/vector.svg" class="svg0"><b>LOOK BETTER</b></div>
				<div class="svg1"><img src="image/Heart.svg" class="svg2"><b>FEEL BETTER</b></div>
				<div class="svg3"><img src="image/star.svg" class="svg4"><b>LOOK BETTER</b></div>
		 
				<!--banner section starts-->
				<section class="banner0">
						<div class="bg0">					
							<div class="box0">
								<div class="vector0"><img src="image/logo4.jpg"></div>
								<div class="look0"><b>Customized Nutrition</b></div>					
								<div class="look1"><b>Do you want to feel better? Do you wish<br>your clothes fit differently?</b></div>	
								<div class="look2">LEARN MORE</div>						
							</div>
							<div class="box3">
								<div class="heart0"><img src="image/logo3.jpg"></div>
								<div class="feel0"><b>Ideal Protein</b></div>
								<div class="feel1"><b>Ideal Protein is a three-phased, medically<br>designed protocol that promotes repaid<br>fat loss while maintaining lean muscle<br>mass. With weekly one-on-one</b></div>
								<div class="feel2">LEARN MORE</div>	
							</div>
						</div>
			    </section>		
			  <!--banner section ends-->		 
		</section>
		<!--section end-->
		 
		     <img src="image/logo6.jpg" width="100%" class="game"> 
			 
		<div class="game0"><b>Ideal Protein</b></div>	 
		<div class="game1"><b>The power to lose weight and reset your health exists inside of you. Our<br>coaches and ketogenic weight loss science have the power to ignite<br>it all.</b></div>	 
	    <div class="game2"><b>LEARN MORE</b></div>
		
		<div class="ideal00"><b>IDEAL PROTEIN</b></div>
					<h1 class="heading00">How You Transform With the<br> 3-Phase Ideal Protein Protocol
						<div class="view00"><b>VIEW ALL</b></div>
					</h1>
					
		<!--main start-->			
		<main>
			<!--section starts-->
			<section>		    
				<div class="border00">					
					<a class="pointer00">
					<div class="weight00">
						<div class="the00"><b>THE FIRST PHASE</b></div>
						<h1 class="loss00">Weight Loss</h1>
						<div class="reset00">Reset body to burn fat and lose weight.</div>
						<div class="learn__00"><b>LEARN MORE<img src="image/right0.png" width="20" class="img"></b></div>
					</div>
					<div class="weight100">
						<div class="second00"><B>THE SECOND PHASE</B></div>
						<h1 class="stable00">Stablization</h1>
						<div class="mind00"> Reset mind to maintain a healthy weight and build healthy habits.</div>
						<div class="learn__00"><b>LEARN MORE<img src="image/right0.png" width="20" class="img"></b></div>
					</div>
					<div class="weight200">
						<div class="third00"><b>THE THIRD PHASE</b></div>
						<h1 class="main00">Maintenance</h1>
						<div class="possible00">Reset possible and live your fullest,healthiest,best life yet.</div>
						<div class="learn__00"><b>LEARN MORE<img src="image/right0.png" width="20" class="img"></b></div>
					</div>
					</a>
				</div>	
			</section>
			<!--section ends-->
		</main>
		<!--main end-->
				
		<!--CORPORATE WELLNESS start-->
			<div class="tools">CORPORATE WELLNESS</div>
			<div class="tools0"><b>Corporate Wellness<br>Services</b></div>
			<div class="learn__01"><b>LEARN MORE</div>
		
			<div class="tools1">01</div>
			<div class="tools2">Lunch & Learn<br>Workshops</div>
			<div class="tools3">We host free, on-site wellness seminars aimed at<br>reducing or eliminating health issues affecting<br>employee health and work productivity</div>
			<div class="learn__02"><b>LEARN MORE</div>
			<div class="tools4"><img src="image/logo7.jpg" height="550px" width="95%"></div>
			<div class="tools5"><img src="image/logo8.jpg" height="600px" width="60%"></div>
			<div class="tools6">02</div>
			<div class="tools7">Corporate Weight<br>Loss</div>
			<div class="tools8">Our evidence-based, medically-designed protocol<br>allows us to assist companies and their employees<br>in motivationg, supporting and engaging<br>participants and leading them to long-term<br>success and life-changing results. We’ve even<br>got numbers to prove it!</div>
			<div class="learn__03"><b>LEARN MORE</div>
		<!--CORPORATE WELLNESS end-->
		
		<h6 class="idealgg"><b>SUCCESS STORIES</b></h6>
		<h1 class="idealpp">We Not Only Help People, We<br>Change Their Lives.</h1>
		
		<!--main start-->
		<main>
			<!--section starts-->
			<section>
			   <a class="grabgg">
				<div class="bordergg">
					<div class="weightgg">
						<h2 class="lossgg"><img src="image/Jaynie.webp" width="60" class="king" border-radius="">Jaynie Mae Baker</h2>
						<div class="resetgg">My problem area has always been my stomach & despite my best
						efforts, getting rid of it is has been impossible. While I didn't have a lot
						of weight on the scale to lose, it kept me from enjoying my closet full
						of desidner dresses & instead I was stuck camouflaging with bulky
						swaters & jackets. I tried with appetite suppressant pills.</div>
						<div class="learn__gg"><b>READ MORE<img src="image/right0.png" width="20" class="img"></b></div><br><br>
						&nbsp;&nbsp;&nbsp;<img src="image/facebook1.png" width="30">&nbsp;&nbsp;<img src="image/instagram0.png" width="20">
					</div>
					<div class="weight1gg">
						<h2 class="stablegg"><img src="image/Paul1.webp" width="60" class="king0" border-radius="">Paul Woodward Timmins</h2>
						<div class="mindgg">I used to be 281 lbs. I lost some on my own (& gained some too),
						struggling through every diet you've ever heard of, but bottm line...
						this program works best, if you follow the plan property. With ideal Protien
						diet & the guidance of BioIntelligent Wellness, I finally have my weight
						management under control. I've been around 160 lbs for almost.</div>
						<div class="learn__gg"><b>READ MORE<img src="image/right0.png" width="20" class="img"></b></div><br><br>
						&nbsp;<img src="image/facebook1.png" width="30">&nbsp;<img src="image/instagram0.png" width="20">
					</div>
				  </div>	
			   </a>
			</section>
			<!--section ends-->
		</main>
		<!--main ends-->
     
        <h6 class="ideal55"><b>CLINICALLY APPROVED</b></h6>
		<h1 class="ideal66">Providers speak to our<br>success</h1>
		
		<!--main start-->
		<main>
			<!--section starts-->
			<section>
			   <a class="grab55">
				<div class="border55">
					<div class="weight55">
						<h2 class="loss55"><img src="image/Aliza.webp" width="60" class="king55" border-radius="">Dr. Aliza Cicerone</h2>
						<div class="reset55">Working with BioIntelligent Wellness has become one of the most invaluable tools that I 
						can offer my patients. Even while approaching disease prevention and management from an integrative perspective,
						there are times when pharmaceuticals, supplement protocols and lifestyle modifications do not produce the desired 
						results. Long term patients of mine</div>
						<div class="learn__55"><b>READ MORE<img src="image/right0.png" width="20" class="img"></b></div>
					</div>
					<div class="weight155">
						<h2 class="stable55"><img src="image/Rothrock.webp" width="60" class="king50" border-radius="">Dr. Douglas Rothrock</h2>
						<div class="mind55">The Ideal Protein Method has proven to be a life-changing catalyst, personally and for my patients.
						Obesity and Metabolic Syndrome are now one of the leading causes of disease and premature death in the U.S. As a cardiologist, 
						the Ideal Protein Method is a wonderful tool I can recommend to my patients that will bring major benefits to their </div>
						<div class="learn__55"><b>READ MORE<img src="image/right0.png" width="20" class="img"></b></div>
					</div>
				  </div>	
			   </a>
			</section>
			<!--section ends-->
		</main>
		<!--main ends--> 
		
		<!--section start-->
		<section>
		  <div class="logos">
          <div class="main"><b>FREE</b></div>
          <div class="main1"><b>Ketogenic Weight Loss Seminar</b></div>
          <div class="main2"><b>WATCH ONLINE</b></div>
          <div class="main3"><b>I'LL COME OFFLINE</b></div>
		  <br><br><br><br><br><br><br><br><br><br></div>
		</section>
		<!--section end-->
		
		  <!--section start-->
		  <section>
				<div class="main4">FAQ's</div>
				<div class="main5">We Are Always Ready To<br>Answer Any Of Your<br>Questions</div>
		  
				<div class="main6">Ideal Protein</div>
				<div class="main7">Ideal Protein Virtual Program</div>
				<div class="main8">Metabolism Testing</div>
				<div class="main9">Corporate Wellness</div>
				<div class="main10">Provider Programs</div>
				<div class="main11">Intuitive Eating</div>
		  </section>
		  <!--section ends-->
		  
		  <div class="end">Is Ideal Protein Safe?<img src="image/plus0.png" width="5%" class="plus"><hr class="hr"><div>  
		  <div class="end0">Is Ideal Protein a high-protein diet?<img src="image/plus0.png" width="5%" class="plus0"><hr class="hr0"><div>  
		  <div class="end1">How much does the Ideal Protein diet cost?<img src="image/plus0.png" width="5%" class="plus1"><hr class="hr1"><div>  
		  <div class="end2">Are there any side effects?<img src="image/plus0.png" width="5%" class="plus2"><hr class="hr2"><div>  
		  <div class="end3">What is ketosis?<img src="image/plus0.png" width="5%" class="plus3"><hr class="hr3"><div> 

          <div class="png">CONTACT</div>		  
          <div class="png0">Ready to get started<br>or have a few more questions?</div>		  
		  
		 <!--form start--> 
		 <form class="form1">
           <input placeholder="First Name *"  type="text*">&nbsp;&nbsp;&nbsp;
           <input placeholder="Last Name*"  type="text">&nbsp;&nbsp;&nbsp;
           <input placeholder="number"  type="number">&nbsp;&nbsp;<br><br><br><Br>
           <input placeholder="E mail*"  type="text">&nbsp;&nbsp;&nbsp;
           
           <Select class="select" >
            <option>Program you're Interested In</option>
            <option>Complimentary Consultation</option>
            <option>Weigth Loss</option>
            <option>Customized Nutrition</option>
            <option>Ideal Protein</option>
            <option>Metabolism</option>
           </Select>&nbsp;&nbsp;&nbsp;
       
           <input placeholder="Message*"  type="text">&nbsp;&nbsp;&nbsp;<br><Br><Br><br>
            <input placeholder="BMxCz"  type="text"><br><Br><br>
              <input type="button" class="b6" value="SEND">
        </form> 
		<!--form end-->  
		
		<!--footer start-->
		   <div class="footer">
		       <image src="image/bio image.png" width="10%" class="footer0">
			   <div class="footer1">Programs&nbsp;&nbsp;&nbsp;Patient&nbsp;&nbsp;&nbsp;Form&nbsp;&nbsp;&nbsp;Blog&nbsp;&nbsp;&nbsp;About As&nbsp;&nbsp;&nbsp;B2B&nbsp;&nbsp;&nbsp;Success Stories</div>
			   <div class="footer2" align="center"><b>CONTACT US</b></div><hr class="footer3">
			   <div class="footer4">Carlsbad<br><br>7220 Avenida Encinas, Suite 110-B<br><br>Carlsbad, CA 92011</div>
			   
			   <div class="header">Working hours</div>
			   <div class="header0">Office hours :</div>
			   <div class="week">Weekdays 8:00 am to 5:00 pm<br>Saturday 8:00 am to 1:00 pm</div>
			   <div class="header2">Coaching Hours:</div>
			   <div class="header3">Weekdays 6:00 am to 7:00 pm<br>Saturday 8:00 am to 2:00 pm</div>
			   
			   <div class="lock">Special Services</div>
			   <div class="lock0">Ideal Protein</div>
			   <div class="lock1">Lunch & Learn Workshops</div>
			   <div class="lock2">Corporate Weight Loss</div>
			   <div class="lock3">Teen Program</div>
			   <div class="lock4">Reduce Prescription Drugs</div>
			   <div class="lock5">Providers</div>
			   
			   <div class="contact">Contacts</div>
			   <div class="contact0">Office/Scheduling</div>
			   <div class="contact1">: 858 228 3644</div>
			   <div class="contact2">Fax:</div>
			   <div class="contact3">760 994 1248</div>
			   <div class="contact4">E-mail:</div>
			   <div class="contact5">info@biointelligentwellness.com</div><hr class="contact6">
			   <div class="real">© Copyright 2023&nbsp;&nbsp;&nbsp;.&nbsp;&nbsp;&nbsp;All rights reserved</div>
			   <div class="real0">Privacy Policy&nbsp;&nbsp;&nbsp;Terms and Conditions</div>
		   </div>
		<!--footer end-->
	</body> 
</html>
