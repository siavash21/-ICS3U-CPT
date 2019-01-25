x = 0
y = 743
action = 'n/a'
gravity = 0.05
time_in_secs = 0
thrust = 0
altitude = (40 + gravity) - thrust
fuel = (600 - thrust)
H_movement = 0
score = 0
spaceship_x_pos = 107 + H_movement
spaceship_y_pos = (47.5 + gravity) - thrust


def setup():
    size(800, 600)

def moving_lines():
    global x,y
    if x <= -800:
        x = 800
    if y <= -800:
        y = 800

    stroke(225)
    line(-56 + x, 530, -40 + x, 520)
    line(-40 + x, 520, -20 +x, 520)
    line(-20 + x, 520, -6 + x, 530)
    line(-6 + x, 530, 50 + x, 530)
    line(50 + x, 530, 70 + x, 500)
    line(70 + x, 500, 90 + x, 450)
    line(90 + x, 450, 120 + x, 420)
    line(120 + x, 420, 130 + x, 414)
    line(130 + x, 414, 135 + x, 410)
    line(135 + x, 410, 140 + x, 402)
    line(140 + x, 402, 150 + x, 390)
    line(150 + x, 390, 165 + x, 390)
    line(165 + x, 390, 185 + x, 400)
    line(185 + x, 400, 200 + x, 450)
    line(200 + x, 450, 220 + x, 480)
    line(220 + x, 480, 240 + x, 500)
    line(240 + x, 500, 250 + x, 530)
    line(250 + x, 530, 280 + x, 545)
    line(280 + x, 545, 295 + x, 530)
    line(295 + x, 530, 310 + x, 535)
    line(310 + x, 535, 320 + x, 500)
    line(320 + x, 500, 335 + x, 480)
    line(335 + x, 480, 345 + x, 470)
    line(345 + x, 470, 360 + x, 455)
    line(360 + x, 455, 378 + x, 430)
    line(378 + x, 430, 398 + x, 415)
    line(398 + x, 415, 434 + x, 450)
    line(434 + x, 450, 449 + x, 500)
    line(449 + x , 500, 456 + x, 509)
    line(456 + x, 509, 468 + x, 515)
    line(468 + x, 515, 475 + x, 515)
    line(475 + x, 515, 480 + x, 490)
    line(480 + x, 490, 495 + x, 475)
    line(495 + x, 475, 505 + x, 460)
    line(505 + x, 460, 520 + x, 440)
    line(520 + x, 440, 540 + x, 450)
    line(540 + x, 450, 555 + x, 475)
    line(555 + x, 475, 570 + x, 490)
    line(570 + x, 490, 585 + x, 500)
    line(585 + x, 500, 600 + x, 515)
    line(600 + x, 515, 620 + x, 520)
    line(620 + x, 520, 630 + x, 530)
    line(630 + x, 530, 670 + x, 530)
    line(670 + x, 530, 690 + x, 545)
    line(690 + x, 545, 720 + x, 545)
    line(720 + x, 545, 735 + x, 485)
    line(735 + x, 485, 750 + x, 470)
    line(750 + x, 470, 770 + x, 470)
    line(770 + x, 470, 793 + x, 520)

    line(50 + y, 520, 70 + y, 500)
    line(70 + y, 500, 90 + y, 450)
    line(90 + y, 450, 120 + y, 420)
    line(120 + y, 420, 130 + y, 414)
    line(130 + y, 414, 135 + y, 410)
    line(135 + y, 410, 140 + y, 402)
    line(140 + y, 402, 150 + y, 390)
    line(150 + y, 390, 165 + y, 390)
    line(165 + y, 390, 185 + y, 400)
    line(185 + y, 400, 200 + y, 450)
    line(200 + y, 450, 220 + y, 480)
    line(220 + y, 480, 240 + y, 500)
    line(240 + y, 500, 250 + y, 530)
    line(250 + y, 530, 280 + y, 545)
    line(280 + y, 545, 295 + y, 530)
    line(295 + y, 530, 310 + y, 535)
    line(310 + y, 535, 320 + y, 500)
    line(320 + y, 500, 335 + y, 480)
    line(335 + y, 480, 345 + y, 470)
    line(345 + y, 470, 360 + y, 455)
    line(360 + y, 455, 378 + y, 430)
    line(378 + y, 430, 398 + y, 415)
    line(398 + y, 415, 434 + y, 450)
    line(434 + y, 450, 449 + y, 500)
    line(449 + y , 500, 456 + y, 509)
    line(456 + y, 509, 468 + y, 515)
    line(468 + y, 515, 475 + y, 515)
    line(475 + y, 515, 480 + y, 490)
    line(480 + y, 490, 495 + y, 475)
    line(495 + y, 475, 505 + y, 460)
    line(505 + y, 460, 520 + y, 440)
    line(520 + y, 440, 540 + y, 450)
    line(540 + y, 450, 555 + y, 475)
    line(555 + y, 475, 570 + y, 490)
    line(570 + y, 490, 585 + y, 500)
    line(585 + y, 500, 600 + y, 515)
    line(600 + y, 515, 620 + y, 520)
    line(620 + y, 520, 630 + y, 530)
    line(630 + y, 530, 670 + y, 530)
    line(670 + y, 530, 690 + y, 545)
    line(690 + y, 545, 720 + y, 545)
    line(720 + y, 545, 735 + y, 485)
    line(735 + y, 485, 750 + y, 470)
    line(750 + y, 470, 770 + y, 475)
    line(770 + y, 475, 800 + y, 530)
    x -= 0.3
    y -= 0.3
    
def spaceship():
    global gravity, thrust, fuel, H_movement, spaceship_x_pos, spaceship_y_pos
    stroke(250, 242, 7)
    fill(255, 0 ,0)
    if keyPressed:
        if (key == CODED):
            if (keyCode == RIGHT):
                H_movement += 0.2
            elif (keyCode == UP):
                thrust += 0.02
                if thrust >= 10:
                    thrust += 0.05
                if thrust >= 20:
                    thrust += 0.1
                if thrust >= 30:
                    thrust += 0.17
            print(thrust)
    spaceship_x_pos = 107 + H_movement
    spaceship_y_pos = (47.5 + gravity) - thrust    
    ellipse(104.5 + H_movement,(40 + gravity) - thrust, 8, 10)
    rect(100 + H_movement,(40 + gravity) - thrust, 8, 7.5)
    rect(100 + H_movement, (47.5 + gravity) - thrust , 1, 4)
    rect(spaceship_x_pos ,spaceship_y_pos , 1, 4)
    
    
def moving_stars():
     for i in range(0, 390, 70):
            fill(255)
            ellipse(random(0, 800), i, 3, 3)
            
def main_menu_screen():
    global x, y, action, gravity, H_movement, thrust 
    if action == 'menu' or action == 'n/a' or action == 'menu_2':
        gravity = 0
        H_movement = 0
        thrust = 0
        background(0)
        textSize(40)
        stroke(255)
        fill(0)
        rect(305, 325, 190, 30)
        rect(305, 265, 190, 30)
        
        fill(255)
        text("MOON LANDER", 255, 200)
        
        textSize(20)
        fill(255)
        text("PLAY", 375, 287)
        text("INSTRUCTIONS", 328, 347)
        if mousePressed:
            if mouseX > 305 and mouseX < 495 and mouseY > 265 and mouseY < 295:
                action = 'gamemode' 
            elif mouseX > 305 and mouseX < 495 and mouseY > 325 and mouseY < 355:
                action = 'instructions'
        moving_stars()
        moving_lines()
                
def pause_screen():
    global action, x, y, gravity, H_movement, thrust
    if action == 'pause':
        gravity = 0
        H_movement = 0
        thrust = 0
        background(16,15,15)
        stroke(255)
        fill(0)
        rect(225, 200, 325, 105)
        rect(240, 255, 135, 35)
        rect(400, 255, 135, 35)
        fill(255)
        textSize(30)
        text("PAUSED", 332, 235)
        textSize(20)
        text("GO BACK", 264, 280)
        text("MAIN MENU", 410, 280)
        if mousePressed:
            if mouseX > 240 and mouseX < 385 and mouseY > 255 and mouseY < 290:
                action = 'menu'
            elif mouseX > 400 and mouseX < 535 and mouseY > 255 and mouseY < 290:
                action = 'menu'
        moving_lines()
        moving_stars()
        spaceship()
        
def lose_screen():
    global action, x, y, losing_text, score, gravity, H_movement, thrust
    import random
    if action == 'lose':
        gravity = 0
        H_movement = 0
        thrust = 0
        background(16,15,15)
        stroke(255)
        fill(0)
        rect(225, 200, 325, 105)
        rect(240, 255, 135, 35)
        rect(400, 255, 135, 35)
        fill(255)
        textSize(30)
        losing_text = ["YOU LOST"]
        text(losing_text[random.choice(range(0, 1))], 318, 235)
        textSize(20)
        text("TRY AGAIN", 262, 280)
        text("MAIN MENU", 410, 280)
        if mousePressed:
            if mouseX > 240 and mouseX < 385 and mouseY > 255 and mouseY < 290:
                action = 'play_again_easy'
            elif mouseX > 400 and mouseX < 535 and mouseY > 255 and mouseY < 290:
                action = 'menu_2'
        moving_lines()
        moving_stars()     
        
def game_mode_screen():
    global x, y, action, gravity, H_movement, thrust
    if action == "gamemode":
        gravity = 0
        H_movement = 0
        thrust = 0
        background(0)
        textSize(40)
        fill(255)
        text("GAME MODES", 268, 140)
        stroke(255)
        fill(0)
        rect(305, 235, 190, 30)
        rect(305, 295, 190, 30)
        rect(305, 355, 190, 30)
        fill(255)
        textSize(20)
        text("GO BACK", 353, 257)
        text("EASY", 375, 317)
        text("HARD", 372, 377)
        if mousePressed:
            if mouseX > 305 and mouseX < 495 and mouseY > 295 and mouseY < 325:
                action = 'Play_easy'
            if mouseX > 305 and mouseX < 495 and mouseY > 235 and mouseY < 265:
                action = 'menu'
            if mouseX > 305 and mouseX < 495 and mouseY > 355 and mouseY < 385:
                action = 'Play_hard'
    moving_lines()
    moving_stars()
    
def play_mode_hard():
    global action, x, y, gravity, thrust, altitude, feul, H_movement, spaceship_x_pos, spaceship_y_pos, score
    if action == 'Play_hard':
        x -= 0.01
        y -= 0.01
        background(0)
        if spaceship_x_pos >= 800:
            H_movement = -107
            fuel = -107
        if keyPressed:
            if (key == TAB):
                action = 'pause'
        if (600 - (thrust +  H_movement)) <= 0:
            action = 'lose'
        fill(255)
        textSize(10)
        text("TRY TO LAND ON THE FLAT SPOTS", 300, 20)
        textSize(10)
        text("ALTITUDE : ", 680, 20)
        text((40 + gravity) - thrust, 740, 20)
        text("FUEL REMAINING :", 20, 20)
        text((600 - (thrust + H_movement)), 110, 20)
        if (600 - (thrust +  H_movement)) <= 75:
            textSize(20)
            fill(253, 31, 31)
            text("WARNING: LOW ON FUEL", 40, 50)
            fill(253, 31, 31)
        if score == 155:
            action == 'win'
        if  (spaceship_x_pos + 1)> 750 + x  and (spaceship_x_pos + 1) < 770 + x and (spaceship_y_pos + 4) >= 470:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 30
        elif  (spaceship_x_pos + 1) > 690 + x and (spaceship_x_pos + 1) < 720 + x and (spaceship_y_pos + 4) >= 545:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 20
        elif  (spaceship_x_pos + 1) > 630 + x and (spaceship_x_pos + 1) < 670 + x and (spaceship_y_pos + 4) >= 530:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 10
        elif  (spaceship_x_pos + 1) > 468 + x and (spaceship_x_pos + 1) < 478 + x and (spaceship_y_pos + 4) >= 515:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 50
        elif (spaceship_x_pos + 1) > 150 + x and (spaceship_x_pos + 1) < 165 + x and (spaceship_y_pos + 4) >= 390:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 45
        elif score == 155:
            action == 'win'
        elif  (spaceship_x_pos + 1)> 750 + y  and (spaceship_x_pos + 1) < 770 + y and (spaceship_y_pos + 4) >= 470:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 30
        elif  (spaceship_x_pos + 1) > 690 + y and (spaceship_x_pos + 1) < 720 + y and (spaceship_y_pos + 4) >= 545:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 20
        elif  (spaceship_x_pos + 1) > 630 + y and (spaceship_x_pos + 1) < 670 + y and (spaceship_y_pos + 4) >= 530:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 10
        elif  (spaceship_x_pos + 1) > 468 + y and (spaceship_x_pos + 1) < 478 + y and (spaceship_y_pos + 4) >= 515:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 50
        elif (spaceship_x_pos + 1) > 150 + y and (spaceship_x_pos + 1) < 165 + y and (spaceship_y_pos + 4) >= 390:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 45  
    fill(0, 225, 0)
    textSize(15)
    text("SCORE :", 620, 50)
    text(score, 700, 50)  
    moving_lines()
    moving_stars()
    spaceship()
    gravity += 0.1

def play_screen():
    global action, x, y, gravity, thrust, altitude, feul, H_movement, spaceship_x_pos, spaceship_y_pos, score
    if action == 'Play_easy' or action == 'play_again_easy' :
        background(0)
        if spaceship_x_pos >= 800:
            H_movement = -107
            fuel = -107
        if keyPressed:
            if (key == TAB):
                action = 'pause'
        if (600 - (thrust +  H_movement)) <= 0:
            action = 'lose'
            
        fill(255)
        textSize(10)
        text("TRY TO LAND ON THE FLAT SPOTS", 300, 20)
        textSize(10)
        text("ALTITUDE : ", 680, 20)
        text((40 + gravity) - thrust, 740, 20)
        text("FUEL REMAINING :", 20, 20)
        text((600 - (thrust + H_movement)), 110, 20)
        if (600 - (thrust +  H_movement)) <= 75:
            textSize(20)
            fill(253, 31, 31)
            text("WARNING: LOW ON FUEL", 40, 50)
            fill(253, 31, 31)
        x = 0
        y = -800
        if score == 155:
            action == 'win'
        if  (spaceship_x_pos + 1)> 750  and (spaceship_x_pos + 1) < 770 and (spaceship_y_pos + 4) >= 470:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 30
        elif  (spaceship_x_pos + 1) > 690 and (spaceship_x_pos + 1) < 720 and (spaceship_y_pos + 4) >= 545:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 20
        elif  (spaceship_x_pos + 1) > 630 and (spaceship_x_pos + 1) < 670 and (spaceship_y_pos + 4) >= 530:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 10
        elif  (spaceship_x_pos + 1) > 468 and (spaceship_x_pos + 1) < 478 and (spaceship_y_pos + 4) >= 515:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 50
        elif (spaceship_x_pos + 1) > 150 and (spaceship_x_pos + 1) < 165 and (spaceship_y_pos + 4) >= 390:
            textSize(10)
            fill(0, 225, 0)
            text("SCORE = +20", 40, 70)
            delay(50)
            thrust = 0
            gravity = 0
            score += 45
        fill(0, 225, 0)
        textSize(15)
        text("SCORE :", 620, 50)
        text(score, 700, 50)
        moving_lines()
        moving_stars()
        spaceship()
        gravity += 0.1    
        
def win_screen():
    global action, x, y, win_text, gravity, H_movement, thrust
    if action == 'win':
        gravity = 0
        H_movement = 0
        thrust = 0
        background(16,15,15)
        stroke(255)
        fill(0)
        rect(225, 200, 325, 105)
        rect(240, 255, 135, 35)
        rect(400, 255, 135, 35)
        fill(255)
        textSize(30)
        win_text = ["YOU WON"]
        text(win_text[random.choice(range(0, 1))], 325, 235)
        textSize(20)
        text("TRY AGAIN", 262, 280)
        text("MAIN MENU", 410, 280)
        if mousePressed:
            if mouseX > 240 and mouseX < 385 and mouseY > 255 and mouseY < 290:
                action = 'play_again_easy'
            elif mouseX > 400 and mouseX < 535 and mouseY > 255 and mouseY < 290:
                action = 'menu_2'
        moving_lines()
        moving_stars() 
    
def instructions_screen():
    global action, x, y, gravity, H_movement, thrust
    if action == 'instructions':
          gravity = 0
          H_movement = 0
          thrust = 0
          background(0)
          stroke(255)
          fill(0)
          rect(25, 30, 68, 35)
          fill(255)
          textSize(20)
          text("BACK", 32, 55)
          stroke(255)
          fill(0)
          rect( 100, 140, 600, 205)
          fill(255)
          textSize(20)
          text("HOW TO PLAY : " , 120,165)
          textSize(15)
          text("-  PRESS & HOLD THE UP ARROW KEY TO THRUST", 155, 200)
          text("-  PRESS & HOLD THE RIGHT ARROW KEY TO MOVE TO THE RIGHT", 155, 230)
          text("-  PRESS & HOLD THE LEFT ARROW KEY TO MOVE TO THE LEFT",155, 260)
          text("-  PRESS & HOLD THE DOWN ARROW KEY TO DO NOTHING", 155, 290)
          text("-  PRESS THE TAB BUTTON TO PAUSE DURING A GAME", 155, 320)
          if mousePressed:
              if mouseX > 25 and mouseX < 93 and mouseY > 30 and mouseY < 75:
                action = 'menu'
          moving_stars()
          moving_lines()
    
def draw():
    play_screen()
    moving_lines()
    moving_stars()
    spaceship()
    pause_screen()
    main_menu_screen()
    instructions_screen()
    game_mode_screen()
    lose_screen()
    win_screen()
    play_mode_hard()
