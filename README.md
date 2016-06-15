# TSORM - TypeScript ORM

TSORM is TypeScript ORM library with annotations support. It is highly inspired by Doctrine 2 framework for PHP and Hibernate framework for Java.

```typescript
@Entity()
class Entity {
  @Id()
  @Column()
  protected $id;
  
  @Column()
  protected $name;
}
```
