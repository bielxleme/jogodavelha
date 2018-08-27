# jogodavelha
 //Código dos botões (btn) para alteração de imagens e  da ordem de jogabilidade
private void btn2ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        
        if(semRepet2 ==0){
        lblQC.setVisible(false);
        if(nm == 0){
           if(x1){
           btn2.setIcon(iconX);
           marco = 1.2 ;
           
       } else if(o1){
           btn2.setIcon(iconO);
           marco = 2.2;
       }
       }else if(nm ==1){
           if(x2){
           btn2.setIcon(iconX);
           marco = 3.2 ;
           
       } else if(o2){
           btn2.setIcon(iconO);
           marco = 4.2 ;
       }
           
       }
         
      if(nm == 0){
           nm =1;
           if(x1 || o1){
               lblComecar.setText(lblJ2.getText());
           }else if(x2 || o2){
               lblComecar.setText(lblJ1.getText());
           }
       }else{
           nm = 0;
       }
       semRepet =1;
       }
    }                   
