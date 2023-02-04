#include<GL/gl.h>
#include<GL/glu.h>
#include<GL/glut.h>

void MyInit()
{
glClearColor(1,0,0,1);
glColor3f(0,1,0);
}

void draw()
{
glClear(GL_COLOR_BUFFER_BIT);
glPointSize(10);

glBegin(GL_LINE_LOOP);
glVertex2f(-0.5,0.5);
glVertex2f(0.5,0.5);
glVertex2f(0.5,-0.5);
glVertex2f(-0.5,-0.5);
glEnd();
glFlush();
}


int main(int c, char*v[])
{
glutInit(&c,v);
glutInitWindowPosition(100,100);
glutInitWindowSize(400,400);
glutInitDisplayMode(GLUT_RGB);
glutCreateWindow("First Window");

MyInit();
glutDisplayFunc(draw);
glutMainLoop();
return 0;
}
